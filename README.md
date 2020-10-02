# REFADE
(Retrieval ANDROID Executables Malware Analysis)

## Commercial Antivirus Limitation

Technically, the modus operandi for the identification of malicious files and servers refers to consult in named blacklist databases. The VirusTotal platform issues the diagnoses regarding malignant characteristics related to files and web servers.

When it comes to suspicious files, VirusTotal issues the diagnostics provided by the world's leading commercial antivirus products. Regarding suspicious web servers, VirusTotal uses the database responsible for sensing virtual addresses with malicious practices.

VirusTotal has Application Programming Interface (APIs) that allow programmers to query the platform in an automated way and without the use of the graphical web interface. The proposed paper employs two of the APIs made available by VirusTotal. The first one is responsible for sending the investigated files to the platform server. The second API, in turn, makes commercial antivirus diagnostics available for files submitted to the platform by the first API.

Initially, the executable malwares are sent to the server belonging to the VirusTotal platform. After that, the executables are analyzed by the 86 commercial antiviruses linked to VirusTotal. Therefore, the antivirus provides its diagnostics for the executables submitted to the platform. VirusTotal allows the possibility of issuing three different types of diagnostics: malware, benign and omission.

Then, through the VirusTotal platform, the proposed paper investigates 77 commercial antiviruses with their respective results presented in Table 2. We used 1600 malicious executables for ANDROID obtained from the REFADE database. The goal of the work is to check the number of virtual pests cataloged by antivirus. The motivation is that the acquisition of new virtual plagues plays an important role in combating malicious applications. Therefore, the larger the database of malwares blacklisted, the better it tends to be the defense provided by the antivirus.

As for the first possibility of VirusTotal, the antivirus detects the malignity of the suspicious file. In the proposed experimental environment, all submitted executables are public domain malwares. Therefore, in the proposed study, the antivirus hits when it detects the malignity of the investigated executable. Malware detection indicates that the antivirus provides a robust service against cyber-intrusions. As larger the blacklist database, better tends to be the defense provided by the antivirus.

In the second possibility, the antivirus attests to the benignity of the investigated file. Therefore, in the proposed study, when the antivirus attests the benignity of the file, it is a case of a false negative – since all the samples are malicious. That is, the investigated executable is a malware; however, the antivirus attests to benignity in the wrong way.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

Table 2 shows the results of the evaluated 86 antivirus products. Only two of these antiviruses scored above 90%. These antiviruses were: Symantec Mobile Insight and K7GW. Malware detection indicates that these antivirus programs provide an efficient service against cyber-intrusions.

A major adversity in combating malicious applications is the fact that antivirus makers do not share their malware blacklists due to commercial disputes. Through Table 2 analyse, the proposed paper points to an aggravating factor of this adversity: the same antivirus vendor does not even share its databases between its different antivirus programs. Note, for example, that McAfee and McAfee-GW-Edition antiviruses belong to the same company. Their blacklists, though robust, are not shared with each other. Therefore, the commercial strategies of the same company hinder the confrontation with malware. It complements that antivirus vendors are not necessarily concerned with avoiding cyber-invasions, but with optimizing their business income.

Malware detection ranged from 0% to 93,71%, depending on the antivirus being investigated. On average, the 77 antiviruses were able to detect 32,60% of the evaluated virtual pests, with a standard deviation of 38,43. The high standard deviation indicates that the detection of malicious executables may suffer abrupt variations depending on the antivirus chosen. It is determined that the protection, against cybernetic invasions, is due to the choice of a robust antivirus with a large and updated blacklist.

As for the false negatives, BitDefender, Baidu and Panda antiviruses, wrongly stated that malware was benign in more than 95% of cases. On average, antiviruses attested false negatives in 43,34% of the cases, with a standard deviation of 41,22. Tackling the benignity of malware can lead to irrecoverable damage. A person or institution, for example, would rely on a particular malicious application when, in fact, it is malware.

Acronis, eScan, Palo Alto Networks, Sophos AV-Sophos, SentinelOne (Static-ML), SecureAge APEX, CrowdStrike Falcon, Sangfor Engine Zero, Sophos ML and Trapmine antivirus companies have not omitted opinion on any of the 1600 samples malicious. Therefore, about 13% of antivirus softwares were not able to diagnose any of the malicious samples. On average, the antiviruses were missing in 24.06% of the cases, with a standard deviation of 41.33. The omission of the diagnosis points to the limitation of these antiviruses that have limited blacklists for detection of malware in real time.

It is included as adversity, in the combat to malicious applications, the fact of the commercial antiviruses do not possess a pattern in the classification of the malwares as seen in Table 3. We choose 3 of 1600 REWEMA malwares samples in order to exemplify the miscellaneous classifications of commercial antiviruses. The chosen malware are Backdoor.IRC.Darkirc.exe, Backdoor.Win32.Zomby.exe e Constructor.VBS.Alamar.20.exe. In this way, the time when manufacturers react to a new virtual plague is affected dramatically. As there is no a pattern, antiviruses give the names that they want, for example, a company can identify a malware as "Malware.1" and a second company identify it as "Malware12310". Therefore, the lack of a pattern, besides the no-sharing of information among the antivirus manufacturers, hinders the fast and effective detection of a malicious application.

###### Table 2 Results of 77 commercial antiviruses:

Antivirus |	Deteccion (%) |	False Negative (%) |	Omission (%)
--------- | ------------- | ------------------ | -------------
Symantec Mobile Insight |	93,71% |	6,12% |	0,17%
K7GW |	90,17% |	9,58% |	0,25%
ESET-NOD32 |	88,25% |	11,71% |	0,04%
Ikarus |	87,04% |	8,33% |	4,62%
CAT-QuickHeal |	86,54% |	13,29% |	0,17%
McAfee|	84,71% |	15,04% |	0,25%
Avira (no cloud) |	83,96% |	15,79% |	0,25%
Fortinet |	83,58% |	14,79% |	1,62%
Trustlook |	83,50% |	14,50% |	2,00%
NANO-Antivirus |	83,46% |	16,29% |	0,25%
AhnLab-V3 |	82,92% |	17,08% |	0%
Symantec |	82,88% |	16,54% |	0,58%
Qihoo-360 |	82,58% |	17,42% |	0%
Avast-Mobile |	82,25% |	17,71% |	0,04%
Sophos AV |	82,25% |	17,33% |	0,42%
DrWeb |	81,79% |	18,04% |	0,17%
ZoneAlarm by Check Point |	81,67% |	17,96% |	0,38%
Comodo |	81,58% |	18,12% |	0,29%
Kaspersky |	81,12% |	17,46% |	1,42%
Alibaba |	81,08% |	18,83% |	0,08%
MAX |	80,67% |	19,29% |	0,04%
McAfee-GW-Edition |	78,75% |	21,17% |	0,08%
Tencent |	76,54% |	23,42% |	0,04%
F-Secure |	74,50% |	19,42% |	6,08%
Cyren |	70,21% |	29,58% |	0,21%
Microsoft |	66,08% |	33,38% |	0,54%
AVG |	63,67% |	33,79% |	2,54%
Avast |	63,50% |	33,46% |	3,04%
Jiangmin |	63,29% |	36,62% |	0,08%
ClamAV |	56,21% |	42,33% |	1,46%
Antiy-AVL |	43,17% |	55,75% |	1,08%
MaxSecure |	26,58% |	5,67% |	67,75%
AegisLab |	18,96% |	80,54% |	0,50%
Zoner |	12,17% |	87,75% |	0,08%
TrendMicro-HouseCall |	9,83% |	89,25% |	0,92%
Zillya |	6,88% |	92,21% |	0,92%
F-Prot |	2,21% |	95,17% |	2,62%
GData |	1,88%	| 98,04% |	0,08%
Emsisoft |	1,71% |	98,17% |	0,12%
BitDefender |	1,71% |	98,12% |	0,17%
Arcabit |	1,67% |	98,33% |	0%
FireEye |	1,46% |	98,04% |	0,50%
Rising |	1,25% |	98,62% |	0,12%
Ad-Aware |	1,17%	| 98,75% |	0,08%
TrendMicro |	0,54% |	86,12% |	13,33%
Baidu |	0,25%	| 98,33% |	1,42%
Yandex |	0,17% |	99,21% |	0,62%
ViRobot |	0,08% |	99,92% |	0%
Panda |	0,08% |	99,75% |	0,17%
VBA32 |	0,08% |	99,46% |	0,46%
TotalDefense |	0,04% |	99,33% |	0,62%
AVware |	0,04% |	0,21% |	99,75%
SUPERAntiSpyware |	0% |	100% |	0%
Kingsoft |	0% |	100% |	0%
K7AntiVirus |	0% |	99,96% |	0,04%
TACHYON |	0% |	99,96% |	0,04%
CMC |	0% |	99,92% |	0,08%
Malwarebytes |	0% |	99,29% |	0,71%
Bkav |	0% |	98,33% |	1,67%
ALYac |	0% |	88,21% |	11,79%
VIPRE |	0% |	73,58% |	26,42%
BitDefenderTheta |	0% |	5,71% |	94,29%
Endgame |	0% |	0,42% |	99,58%
Cybereason |	0% |	0,21% | 99,79%
eGambit |	0% |	0,17% |	99,83%
Webroot |	0% |	0,08%	| 99,92%
Cylance |	0% |	0,04% |	99,96%
eScan |	0% |	0% |	100%
Acronis |	0% |	0% |	100%
Palo Alto Networks |	0% |	0% |	100%
Sophos AV-Sophos |	0% |	0% |	100%
SentinelOne (Static ML) |	0% |	0% |	100%
SecureAge APEX |	0% |	0% |	100%
CrowdStrike Falcon |	0% |	0% |	100%
Sangfor Engine Zero |	0% |	0% |	100%
Sophos ML |	0% |	0% |	100%
Trapmine |	0% |	0% |	100%


###### Table 3 Miscellaneous classifications of commercial antiviruses:

