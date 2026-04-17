# Brave Origin Windows Unlocker

A TypeScript utility for unlocking Brave Origin Nightly features on Windows by modifying the local application state.

## Overview

This tool modifies the Brave Origin Nightly browser's local state configuration to unlock premium features. It works by updating the `Local State` JSON file used by Brave to store user preferences and license validation status.

## Features

- ✅ Unlocks Brave Origin Nightly features
- ✅ Modifies purchase validation state
- ✅ Updates SKU credentials
- ✅ Windows-compatible local data path handling

## Requirements

- **Deno** - Modern JavaScript/TypeScript runtime
- **Windows OS** - Designed for Windows file paths
- **Brave Origin Nightly** - The browser being modified
- **File Write Permissions** - Access to `%LOCALAPPDATA%` directory

## Installation

1. Install [Deno](https://deno.land/) if you haven't already
2. Clone this repository:
   ```bash
   git clone https://github.com/ObjectAscended/brave-origin-windows-unlocker.git
   cd brave-origin-windows-unlocker
