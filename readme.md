# Env

- OSX
- Node v11.15.0
- NPM 6.7.0

# Repro Steps

`npm install && npm start`

1. Edit `# Test 1` -> `# Test 1!` // Observe update
2. Scroll to slide 2
3. Edit `# Test 2` -> `# Test 2!` // Observe no update
4. Stay on slide 2 -> update `# Test 1!` -> `# Test 1?` // observe both slides update
