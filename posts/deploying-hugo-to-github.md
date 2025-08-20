+++
date = '2025-09-13T10:00:00+08:00'
draft = false
title = 'Deploying Hugo to GitHub Pages'
authors = ['gzl']
categories = ['Technology']
tags = ['Hugo', 'Deployment', 'GitHub']
+++

# Deploying Hugo to GitHub Pages

GitHub Pages is a great platform for hosting static websites created with Hugo.

## Prerequisites

Before deploying, make sure you have:

1. A GitHub account
2. A Hugo website
3. Git installed on your computer

## Step-by-Step Guide

### 1. Create a GitHub Repository

Create a new repository named `username.github.io`, where `username` is your GitHub username.

### 2. Configure Hugo for GitHub Pages

Update your Hugo configuration file (`hugo.toml`) with the correct base URL.

### 3. Generate Your Website

Run `hugo` to generate your static website files in the `public` directory.

### 4. Deploy to GitHub Pages

Use Git to commit and push your generated files to the `gh-pages` branch of your repository.

### 5. Configure GitHub Pages Settings

In your repository settings, set the GitHub Pages source to the `gh-pages` branch.

## Automation with GitHub Actions

You can automate the deployment process using GitHub Actions to build and deploy your site whenever you push changes to your repository.