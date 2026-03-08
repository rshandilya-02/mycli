# 🚀 Dir Manager

> Your terminal just got a little cooler.

**Dir Manager** is a tiny but funky CLI that lets you manage directories straight from the command line — fast, clean, and with a little attitude.

Built with **Node.js + Commander**, this tool brings simple file system operations into one smooth command-line experience.

---

 dirmanager
  ____  _        __  __
 |  _ \(_)_ __  |  \/  | __ _ _ __   __ _  __ _  ___ _ __
 | | | | | '__| | |\/| |/ _` | '_ \ / _` |/ _` |/ _ \ '__|
 | |_| | | |    | |  | | (_| | | | | (_| | (_| |  __/ |
 |____/|_|_|    |_|  |_|\__,_|_| |_|\__,_|\__, |\___|_|
                                          |___/
Usage: index [options]

A cli for managing a directory

Options:
  -V, --version       output the version number
  -l, --ls [value]    List directory contents
  -m,--mkdir <value>  Create a directory
  -t,touch <value>    Create a file
  -h, --help          display help for command

## ✨ Features

⚡ List directory contents
📁 Create directories instantly
📄 Create files in seconds
🎨 Stylish terminal banner

All from one neat CLI.

---

## 📦 Install

```bash
npm install -g @rshandilya-02/directory_manager
```

Or run instantly:

```bash
npx @rshandilya-02/directory_manager
```

---

## 🧰 Usage

### List files

```bash
directory_manager -l
```

or

```bash
directory_manager --ls ./folder
```

---

### Create directory

```bash
directory_manager --mkdir myFolder
```

---

### Create file

```bash
directory_manager --touch hello.txt
```

---

## 🎛 Example Output

```
Dir Manager

filename        size(KB)      created_at
----------------------------------------
index.js        2.1 KB        2026-03-08
src             0 KB          2026-03-08
README.md       0.4 KB        2026-03-08
```

---

## ⚙ Built With

* Node.js
* Commander.js
* Figlet
* TypeScript

---

## 🧑‍💻 Author

A homosapien

---

## ⭐ If you like it

Don't give any stars , its just basic cli tool , nothing new...
