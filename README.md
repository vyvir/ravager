# Ravager
Ravager is a SRB2 gamemode.

## How to build it?

Install the following dependencies (These are for OpenSUSE, yours may vary):
```
sudo zypper in make nodejs-common
```

Clone the repository:

```
git clone --recursive https://github.com/vyvir/ravager
```

Enter the PAK3 directory:

```
cd ravager ; cd PAK3
```

Install PAK3 dependencies:

```
npm install
```

Go back to parent directory:

```
cd ..
```

Build the pk3:

```
make
```

Test the newly built pk3:

```
make runlinux
```

Build and test the newly built pk3:

```
make buildrunlinux
```

## How can I help?
If you can code, try making a pull request for something you want!
If you can do art, compose, etc. Hit me up at **@vyvim on Discord!**

## Credit
- Ravager by [vyvir](https://github.com/vyvir)

- [Saxa and Luigi's Murder Mystery](https://github.com/Saxashitter/murder-mystery) by [Saxashitter](https://github.com/Saxashitter), [luigi budd](https://github.com/luigi-budd), [Unmatched Bracket](https://github.com/UnmatchedBracket), and [Jisk](https://github.com/Jiskster)

- [PAK3](https://github.com/UnmatchedBracket/PaK3) by [Unmatched Bracket](https://github.com/UnmatchedBracket)

- [Pico's Handbag (Pico Day 2021)](https://www.newgrounds.com/audio/listen/1027918) by [larrynachos](https://larrynachos.newgrounds.com/) / [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)

- [Gritty Metal Loop](https://www.newgrounds.com/audio/listen/945062) by [VoytekPavlik](https://www.newgrounds.com/audio/listen/945062) / [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)

- [URBAN ONSLAUGHT II](https://www.newgrounds.com/audio/listen/1275333) by [AcidHydra101](https://www.newgrounds.com/audio/listen/1275333) / [CC BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) / Edited from original
