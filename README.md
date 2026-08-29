<div align="center">

# ⚡ System Benchmark

### A fast, browser-based diagnostic suite for measuring real-world system performance.

**Compute • Memory • Sorting • DOM • Rendering**

<br>

![HTML](https://img.shields.io/badge/HTML5-Benchmark-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-7FCE8C?style=for-the-badge)
![Local](https://img.shields.io/badge/Processing-100%25_Local-4FD1C5?style=for-the-badge)

<br>

**No installation. No server. No data collection.**

Just open it and run.

</div>

---

## 🔥 What is it?

**System Benchmark** is a lightweight diagnostic suite that measures several areas of your computer directly through the browser.

Instead of relying on hardware names alone, the suite runs actual workloads and compares the results against its calibrated baseline.

A complete run takes roughly **10 seconds**.

Everything happens locally inside your browser.

> Your benchmark data never leaves the page.

---

## 📊 What's Tested?

| Test           | What it measures                                                     |  Output  |
| :------------- | :------------------------------------------------------------------- | :------: |
| 🧠 **Compute** | Mathematical CPU throughput using repeated trig and root operations  |  `ops/s` |
| 💾 **Memory**  | Sequential typed-array read/write throughput                         |  `MB/s`  |
| 🔀 **Sort**    | JavaScript comparison sorting across hundreds of thousands of values | `elem/s` |
| 🌐 **DOM**     | Browser node creation, mounting, layout and teardown                 |  `ops/s` |
| 🎨 **Render**  | Sustained Canvas rendering performance                               |   `FPS`  |

Each test produces its own score before being combined into the final system result.

---

## 🏆 Composite Score

Once all tests finish, System Benchmark calculates a **composite performance score**.

```text
S   Exceptional
A   Excellent
B   Good
C   Fair
D   Weak
F   Poor
```

The dashboard also breaks performance down by subsystem so you can quickly see where your machine performs well and where it may be struggling.

---

## 🖥️ System Overview

Where supported by the browser, the suite also detects useful system information including:

```text
CPU logical core count
GPU / WebGL renderer
Reported memory capacity
Memory throughput
Rendering performance
```

Browser privacy restrictions may prevent certain hardware details from being exposed.

That's expected.

---

## 🛠️ Upgrade Suggestions

The benchmark doesn't stop at a number.

After testing, the suite analyzes the results and can flag areas such as:

**CPU bottlenecks**
Potential background load, thermal throttling, or weak compute performance.

**GPU limitations**
Low rendering throughput or graphics performance.

**Memory bandwidth**
Slow sequential memory performance.

**RAM capacity**
Potential memory pressure during modern multitasking.

If everything looks healthy, it'll tell you that too.

---

## 🧪 Built for Repeatable Testing

The suite includes protections for situations that can distort browser benchmarks.

For example, Canvas rendering relies on `requestAnimationFrame`, which browsers may heavily throttle when a tab isn't visible.

System Benchmark accounts for cases like this instead of quietly treating invalid measurements as legitimate results.

The diagnostic log also records what happened during each run, making unusual results easier to spot.

---

## 🚀 Running It

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Then open:

```text
system-benchmark.html
```

in a modern browser.

Or just download the HTML file and double-click it.

**No npm.**
**No build process.**
**No backend.**
**No dependencies.**

---

## 🎯 Getting Better Results

For more consistent benchmark runs:

1. Close unnecessary applications and heavy browser tabs.
2. Keep the benchmark tab visible while testing.
3. Plug laptops into power when comparing maximum performance.
4. Allow the system to cool down before repeated testing.
5. Run the benchmark several times instead of trusting one result.

Browser benchmarks are affected by thermals, power management, browser versions, background processes, and operating-system scheduling.

Small differences between runs are normal.

---

## 🔒 Privacy

System Benchmark is intentionally self-contained.

```text
✓ No accounts
✓ No analytics
✓ No tracking
✓ No benchmark uploads
✓ No external API
✓ No hardware information sent anywhere
```

All benchmark calculations happen on your device.

---

## 🎨 Interface

The interface was designed around a compact diagnostic-console style rather than a traditional benchmark spreadsheet.

It includes:

* Live scope visualization
* Individual benchmark cards
* CPU, GPU, memory and RAM overview
* Animated composite gauge
* Performance tier indicator
* Upgrade recommendations
* Timestamped diagnostic log
* Run checksum
* Responsive layout
* Reduced-motion support

---

## ⚠️ Benchmark Limitations

This is a **browser benchmark**, not a replacement for dedicated native benchmarking software.

Results are influenced by the browser's JavaScript engine, graphics implementation, security restrictions, power state and operating system.

The scores are best used for:

```text
Comparing repeated runs on the same machine
Spotting obvious performance problems
Comparing browsers
Testing changes to system configuration
Getting a quick performance overview
```

Treat the numbers as diagnostic indicators rather than laboratory-grade hardware measurements.

---

<div align="center">

## ⚡ Diagnostic Suite

**Five tests. One score. About ten seconds.**

Built with plain HTML, CSS and JavaScript.

`Rev 2.4`

</div>
