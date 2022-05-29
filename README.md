# Internet-of-Things_using_Medical_and_Network-Data
Introducing IoT systems to healthcare applications has made it possible to remotely monitor patients’ information and provide proper diagnostics whenever needed. However, providing high-security features that guarantee the correctness and confidentiality of patients’ data is a significant challenge. Any alteration to the data could affect the patients’ treatment, leading to human casualties in emergency conditions. Due to the high dimensionality and prominent dynamicity of the data involved in such systems, machine learning has the promise to provide an effective solution when it comes to intrusion detection. However, most of the available healthcare intrusion detection systems either use network flow metrics or patients’ biometric data to build their datasets.

The WUSTL-EHMS-2020 dataset was created using a real-time Enhanced Healthcare Monitoring System (EHMS) testbed. This testbed collects both the network flow metrics and patients' biometrics due to the scarcity of a dataset that combines these biometrics. 

The type of attacks included in this dataset is man-in-the-middle attacks: spoofing and data injection. The spoofing attack is only to sniff the packets between the gateway and the server, which violates the patient's data confidentiality. The data injection attack is used to modify the packets on-the-fly, which violates the data's integrity.

The EHMS testbed is divided into four parts: medical sensors, gateway, network, and control with visualization.

The data flow starts from the sensors attached to the patent's body, to the gateway. Then the gateway sends the data to the server for visualization via the switch and router. An attacker can intercept these data before they arrive at the server. The Intrusion Detection System (IDS) is responsible for capturing the real-time network flow traffic and the patient's biometric data and abnormalities detection. 

The Real-time dataset collect from the reference research paper A. A. Hady, A. Ghubaish, T. Salman, D. Unal and R. Jain, "Intrusion Detection System for Healthcare Systems Using Medical and Network Data: A Comparison Study," in IEEE Access, vol. 8, pp. 106576-106584, 2020, doi: 10.1109/ACCESS.2020.3000421. https://ieeexplore.ieee.org/document/9109651
