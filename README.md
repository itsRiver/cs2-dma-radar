# CS2 DMA Radar

> Fork of [CS2_DMA_Radar](https://github.com/MoZiHao/CS2_DMA_Radar) with some improvements.

![Capture](https://github.com/rabume/cs2-dma-radar/assets/19410629/b2097ba8-eda5-4a09-bf11-e643f0699c8b)

> If you just want to use the radar, you can download the latest release [here](https://github.com/rabume/cs2-dma-radar/releases)
> Requirements to run latest release: [JDK 21](https://adoptium.net/temurin/releases/?os=windows&arch=x64&package=jdk&version=21)

## 🚀 Usage

After you complied or downloaded the latest release, you can start the radar with the following command:

```bash
java -jar CS2DMA-1.0.jar
```

Then you should be able to access the radar at http://localhost:8080

## ⚡️ Requirements

- nodejs (>= 20.3.0)
- Java Development Kit (>= 20)
- Apache Maven (>= 3.8.7)
- make (>= GNU Make 4.4.1)

## 🛠️ Build

1. Install frontend dependencies: `cd client && npm i`
2. Move back to the root directory: `cd ..`
3. Build application: `make build`
4. Move to the release directory: `cd release`
5. Start the application: `java -jar CS2DMA-1.0.jar`

## Offsets

The offsets are store in a file called `offsets.json` in the root directory of the application.
To get the latest offsets you can the [cs2-dumper](https://github.com/a2x/cs2-dumper) by a2x.
If you don't want to dump them yourself, you can use the offsets from [here](https://github.com/a2x/cs2-dumper/blob/main/generated/offsets.rs).
