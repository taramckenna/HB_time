# HB_time
graphs showing the exponential decrease of the battery life of the HB pumps

df = pd.read_csv("__.csv")

sns.lineplot(data=df, x="Switch-on", y="Time", hue="Pump")

plt.ylabel("Time Before Pump Switches Off")
plt.xlabel("Switch-on Attempt Number")
plt.title("Time it takes for HB & Non-HB pumps to lose battery life")
plt.show()
