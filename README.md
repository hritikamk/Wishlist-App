# Wishlist (SwiftUI + SwiftData)

A simple wishlist app built during my early SwiftUI phase — and my **first time using SwiftData** for on-device persistence. Add things you want to do/buy/learn, and swipe to delete. ✅

## Overview
- Built with **SwiftUI** and **SwiftData** (Apple’s modern persistence framework).
- Minimal model: `@Model class Wish { var title: String }`
- Uses `@Query` for live list updates and `@Environment(\.modelContext)` for writes.
- Includes Preview seeding via `.modelContainer(for:inMemory:)`.

## Features
- ➕ Add a new wish (inline alert / text field).
- 📜 Live-updating list of wishes.
- 🗑️ Swipe-to-delete.
- 🧪 Previews with in-memory sample data.

## Tech Stack
- **Language:** Swift
- **Frameworks:** SwiftUI, SwiftData
- **iOS:** 17+ (Xcode 15+ recommended)
- **Architecture:** Simple SwiftUI view hierarchy with SwiftData model

