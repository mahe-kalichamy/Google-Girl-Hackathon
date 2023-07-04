# Google-Girl-Hackathon
Verilog Program to detect faults at specific locations/nodes that occur during the manufacturing of chips before they are delivered to end users.

To set up a Verilog environment, you'll need a few tools and resources. Here's a general guide to help you get started:

1. Verilog Simulator:

Choose a Verilog simulator such as ModelSim, VCS, or Xilinx Vivado.
Install the simulator according to the documentation provided by the vendor.
Make sure the simulator is compatible with your operating system.

2. Integrated Development Environment (IDE):

Select an IDE that supports Verilog development. Some popular choices are Visual Studio Code with Verilog plugins, Quartus Prime, or Xilinx Vivado.
Install the IDE and any required extensions or plugins.

3. Verilog Compiler:

Verify if your chosen simulator includes a Verilog compiler. If not, you may need to install a separate Verilog compiler such as Icarus Verilog (iverilog) or Verilator.
Install the Verilog compiler based on the documentation provided.

4. Testbench and Design Files:

Create a new directory for your Verilog project.
Write the Verilog design file (.v) with your module implementation.
Write a testbench file (.v) to simulate and test your design.
Save both files in the project directory.

5.Compilation and Simulation:

Open the terminal or command prompt and navigate to your project directory.
Use the Verilog compiler to compile your design and testbench files. For example, using Icarus Verilog:
  --> iverilog -o simulation_file.vvp design_file.v testbench_file.v
Run the simulation using the compiled file. For example, using Icarus Verilog:
 --> vvp simulation_file.vvp

