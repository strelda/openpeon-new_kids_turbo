# New Kids Turbo Sound Pack for [OpenPeon](https://openpeon.com) (CESP v1.0)

A Slovak/Czech sound pack featuring classic voice lines from the comedy movie **New Kids Turbo** (featuring Richard, Robbie, Rikkert, Barry, and Gerrie).

This sound pack is compliant with the **Coding Event Sound Protocol (CESP) v1.0** specification (see the [OpenPeon Specification](https://openpeon.com)) and can be loaded into any compatible agentic IDE (like Claude Code, Cursor, Codex, etc.).

## Categories & Sounds

Each category contains 10 carefully selected iconic quotes:

- **`session.start`**: Greetings and start of session quotes (e.g., *Čau zlatko*, *V maskantje se nedáme*, *Richard Batsbak*, etc.)
- **`task.acknowledge`**: Processing / Acknowledged quotes (e.g., *Obednal*, *Ja to upracem*, *Ututláte to*, etc.)
- **`task.complete`**: Success / Completion quotes (e.g., *Dobrá práca chalan*, *Kurva to sa ti podarilo*, *Špica*, *Rickert už nieje panic*, etc.)
- **`task.error`**: Error / Failure quotes (e.g., *Ty kretén*, *Kurna kurna kurna*, *No dopiče*, *No doriti*, etc.)
- **`input.required`**: Waiting for user action or permission (e.g., *Cože pomoc?*, *Čo si povedal?*, *Neviem*, etc.)
- **`resource.limit`**: Limit hit / Money issues (e.g., *Nemám prachy ty kokot*, *Daj nám viac prachov pičus*, *Vydrbaná sprostá kríza*, etc.)
- **`user.spam`**: Spam / Too fast inputs (e.g., *Drž hubu ty vytrasený pičus*, *A teraz vypadni*, *Vypadnite debili*, etc.)
- **`session.end`**: Exit / Bye quotes (e.g., *Majsa*, *Tak sa maj*, *Poďme na pivo*, etc.)
- **`task.progress`**: Long task running checks (e.g., *Som v pohode*, *Pianko pohodíčka*, *Pokročili prekvapivo rýchlo*, etc.)

## Installation & Activation

To use this sound pack in an [OpenPeon](https://openpeon.com)-compliant environment, follow these instructions to install it manually:

### 1. Clone from GitHub
Create the standard OpenPeon packs directory if it doesn't exist, and clone this repository into it under the name `new-kids-turbo`:
```bash
mkdir -p ~/.openpeon/packs
git clone git@github.com:strelda/openpeon-new_kids_turbo.git ~/.openpeon/packs/new-kids-turbo
```

### 2. Verify Directory Structure
Ensure the cloned repository is correctly positioned:
* **Manifest path:** `~/.openpeon/packs/new-kids-turbo/openpeon.json`
* **Sounds directory:** `~/.openpeon/packs/new-kids-turbo/sounds/`

### 3. How to Activate
Once cloned into the correct directory, activate the sound pack within your client:
* **For CLI tools or IDE extensions:** Open your client configuration (e.g., config file or settings) and set the active sound pack name to `new-kids-turbo`.
* **Via command line (if supported by your client):**
```bash
peon packs use new-kids-turbo
```
### 4. Test the Sound Pack
After activation, test the sound pack by triggering various events in your IDE or client. To test it, see categories above and run e.g.
```bash
peon preview task.complete
```

## License

This sound pack is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC-BY-NC-4.0)** license. The original audio snippets belong to the creators of the movie *New Kids Turbo*.

Special thanks to TM, from whose site I obtained the audio.