# ReaScripts

Reaper utility scripts.

## Installation

Drop the files into your Reaper scripts folder (Options > Show resource path in explorer/finder). Runm them from the ReaScript development environment.


## Usage

#### MakeMultisampleWave

Creates a long wave file out of many shorter samples suitable for import into Elektron Model:Samples for facilitating creative startpoint wiggling.

To use, create a new empty Reaper project. Drop 120 samples on it, each on a separate track. Run the script. The samples will be shortened to fit into a single beat, and their start positions set to play sequentially. Render the project (with no tail) to create a 60 second wave file containing the 120 samples. Load it into the Model:Samples and have fun.

