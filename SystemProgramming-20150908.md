# Process and File/FS
* Everything is file (incl. Devices).
* FS Abstracts devices into files.

# File as abstraction
## What is file?
* Linear array of bytes.
* A collection of related information
### Difference between addr. space
* File has *variable length* but Address space is *fixed length*.
* File is *persistent* but Address space is *volatile*.
* File is *continuous* but Address space is *non-continuous*

### Difference betwwen DB table
* Record vs. Byte

## File attributes - metadata

## File system structure

TODO: What does **formatting** does?

## Directory structure - problems
* Cyclic-graph dirs.

# Mount
* Seperate device and directory
* Mount?
  * Bind any device to empty directory.

# File commands?
* Create
* Open
* Close
* Seek
* Read
* Write

TODO: Hard link vs Soft link?
