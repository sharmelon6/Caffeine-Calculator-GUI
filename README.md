# Caffeine-Calculator-GUI
This is a caffeine calculator created using MATLAB for a class project. This is the GUI APP version of the code.

# Introduction: 
Today, caffeine is a popular stimulant used by many college students for various reasons, from increasing gym performance to fueling late-night study sessions and preparing for exams. Caffeine engages with the brain by binding to adenosine receptors and increasing the sympathetic nervous system response by increasing the heart rate and blood pressure, as well as increasing adrenaline and cortisol.

CNS activation, along with effects on cardiovascular, respiratory, renal, and muscular systems, are all pharmacological and physiological effects of caffeine and create changes in mood, memory, alertness, and physical and cognitive performance. Caffeine absorption is considered to be linear, with rapid absorption of 99% of caffeine content within 45 minutes of ingestion.  

Caffeine decay is dependent on a multitude of factors, but a general formula can be used with a half-live value given the nature of the breakdown as exponential decay. Caffeine half-life can range from 1.5-9.5 hours depending on the physiological makeup of the user; however, for this calculator, a general value of 5.7 hours was used as the half-life.

Negative side effects of caffeine can include increased blood pressure, increased urine output, insomnia, nervousness, restlessness, increased heart rate, headaches, chest pain, anxiety, irregular heartbeat, or even death (in extreme cases).

The purpose of creating this calculator was to demonstrate not only if a user is ingesting a safe amount of caffeine or not, but also inform them of how long they should wait before taking any other medication or substances, as many drugs have negative interactions with caffeine, including Ephedrine, Antidiabetic drugs, Theophylline, Phenothiazines, Anticoagulant drugs, Tricyclic antidepressants, Asthma medications, Contraceptive drugs, Cimetidine, Clozapine, Dipyraidmole, Disulfuram, Estrogen, Antibiotics, Adenosine, Fluvoxamine, Lithium, Phenzelzine, Selegilizine, Tranycycpromine, Antiplatelets, Pentobarbital, Phenylpropanolamine, Rizuole, Amphetamines, Verpamil, Beta-adrenergic agonists, Carbamazepine, Ethosuximide, Felbamate, Flutamide, Phenytopin, Valproate, Diuretics, Nicotine, Pioglitazone, Flucanozone, Mexiletine, Terbinafine, CYP1A2 inhibitors, Metformin, Methoxsalen, Tiagabine, and Ticlopidine.

# Methods:
In the computational code, the methods used involve many local functions, with 3 key inputs to determine numerous outputs. The three inputs are an estimated amount of caffeine (mg), the user’s body weight (kg), and an estimate of elapsed time since ingestion (min). Using the input, outputs include a safe and maximum limit of caffeine recommended for the user, as well as a percentage comparing input caffeine intake to the limit values. The safe limit is 3 mg per kg of body weight, and the maximum limit is 6 mg per kg per body weight8. Other outputs include an estimated time for breakdown completion, visual markers for a safety rating, and a graph displaying the absorption and decay results.

The graph will demonstrate the caffeine concentration left in the bloodstream and the time it takes to reach a negligible effect. The gauges and bulb at the right of the graph provide more visual markers for the user as a safety assessment of their caffeine levels. 

If the caffeine intake level is below the user's safe limit, it is indicated visually with a green color. If the caffeine intake level is between the user's safe limit and maximum limit, it is indicated visually with a yellow color. If the caffeine intake level is above the user's maximum limit, it is indicated visually with a red color. 

The program provides the user with statistics on their caffeine intake, a calculation for an estimated daily safe and maximum caffeine intake, a calculation for the percentage their intake is compared to their limits, as well as a message, based on each user case, confirming their caffeine intake status. Additional information such as FDA warnings and health warnings about caffeine are included, and time statistics for the amount of time it will take to reduce caffeine levels to negligible effects, the current elapsed time from initial ingestion, as well as time remaining until negligible effects are reached.

# Discussion:
The results are consistent with expectations and physical intuition, as the program was designed to use real-world data and would calculate the results based on the user profile. A suggestion to improve the model would be to indicate on the graph with a marker where the user is and show the full graphical data to include another visual marker for the user. Another way to improve the program would be to show caffeine breakdown past the 30 mg negligible threshold as caffeine can linger for longer than 24 hours in the human body.
