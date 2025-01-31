# nasscom-vsd-soc-design-program
Section 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK
Section 1 tasks:-

In layman's terms, this often called a "CHIP". However, in technicality it is termed as a "PACKAGE". One kind of package, which is used in the arduino board is a QFN - 48 package (Quad Flat No-Leads).

PADS : They act as connectors between the integrated circuit and chip. Pads, simply are structures for sending electrical signals inside the chip. They are strategically placed and made with respect to the pins
CORE : This is the digital logic (i.e. the various gates such as AND, OR, XOR etc and the MUXes) is placed. It carries out all processor functions.
DIE : A die is a part of semiconductor wafer that can be used independently in various devices. It can contain more than one core.

Introduction to RISC 
RISC (Reduced Instruction Set Computer) is a microprocessor architecture that uses a small set of instructions to perform tasks quickly. 

Introduction to Components of Opensource Digital ASIC Design

RTL IPs - they are building blocks written in a hardware description language. These blocks describe the functioning of the circuit at a basic level and are pre designed and verified.
EDA Tools - EDA, which expands to Electronic Design Automation tools are used for design, simulation and verification and the analyzing of circuit designs. Common tools are OpenSTA, OpenRoad etc.
PDK data - Process Design Kit data is a collection of files used to model the fabrication process for EDA tools. It is usually provided by a foundry and include Process Design Rules, Device Models, Digital Standard Cell Libraries and IO libraries.

    Run 'picorv32a' design synthesis using OpenLANE flow and generate necessary outputs.
    Calculate the flop ratio
    Flop Ratio = No. of D Flip Flops/ Total No, of Cells
                = 1613/ 14876
                = 0.108
              
Percentage of D Flip FLops = 10.84% 
