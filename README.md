#DRAMVis: a visualization and comparison tool for DRAMSim2#

Here is a very short guide for how to build this tool: 

1. Install mono, monodevelop and mono winforms, in Ubuntu, you can do this with: 
``` sudo apt-get install libmono-winforms2.0-cil mono monodevelop ```
2. In the DRAMVis directory run: 
``` mdtool build ```
3. Go into the DRAMVis/bin/Debug directory:
``` cd DRAMVis/bin/Debug ```
4. Run DRAMVis
``` mono DRAMVis.exe ```

Unfortunately, at the moment some things have become broken in DRAMVis mainly because 
parameters names in DRAMVis don't agree with the parameter names in DRAMSim2. 
###However, at this time no one in our group has the time to maintain DRAMVis
so you are on your own if you wish to use this software, i.e. it is
unsupported. If you're interested in taking the time to fixup DRAMVis, we'll
happily accept patches.###

