# Documentation

Files API is a project to allow you to manage files programatically. It also provides useful ways to manipulate images, so that you don't need to worry learning or making low-level image manipulation in your project:

- 📁 General purpose file manipulation API.
- 🖼️ Specific helpers for images.
- 🏖️ Easy to use by developers and well documented (aham not yet~).
- 🚀 High performance for whenever you need it most.
- 💰 Cheaper than the alternatives. [see how](#how-is-it-so-cheap).
- 💸 Fixed pricing. No nasty surprises at the end of the month.

## Getting Started

## API

### Auth

### Upload file

### Read image

### Read file

### Delete image

## Free API

## User Guide

The user is the fundamental unit for billing and for the endpoint. Different users are billed separatedly, so for a new project please create a new user.

### Register

### Upgrade

### Dashboard

### Settings

## Libraries

No official library yet in any language.

## Frequently Asked Questions

### How is it so cheap?



How is it so cheap?

We are doing multiple steps to optimize the cost, but basically we are using the best ROI tech and keepin our costs as low as possible:

- **Hosting**: your data is hosted on Backblaze B2 which is ~1/3rd of the cost of S3. Our margin there is 100% of the cost. So we can get a decent margin while costing you ~2/3rds of S3.
- **Bandwidth**: while we have a 0% margin on Backblaze B2's brandwidth costs, we put Bunny CDN on top of it and earn $0.005 for every cached GB. You also save money for every cached image since it reduces an operation and it's faster. Nice incentives here!
- **Operations**: by using the heavily optimized library Sharp.js and setting image size limits, we can keep the operations cheap.
- **Usage**: credits reset at the end of the month, so every credit unused becomes profit for us.
- **Development**: it's [only me](https://francisco.io/) building and deploying this as a side project, so costs are lower.
