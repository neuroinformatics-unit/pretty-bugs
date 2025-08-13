# Pretty Bugs

This is a collection of students' projects, showcasing their work in progress (bugs, artifacts, and anything that is scrappy and unfinished).

## How to share your screenshots

Follow these steps to add your screenshots to the showoff website:

1. **Clone the fork**
   ```bash
   git clone <your-fork-url>
   cd pretty-bugs
   ```

2. **Change the main documentation file**
   Edit `pretty-bugs/docs/source/index.md`

3. **Write a description of your image**
   Add a section describing what your screenshot shows

4. **Add your image**
   Place your image file in `pretty-bugs/docs/source/_static/`

5. **Link the image in the documentation**
   Add the image to `index.md` using this syntax:
   ```markdown
   ![description](_static/my_pic.png)
   ```

6. **Commit and push your changes**
   ```bash
   git add .
   git commit -m "Add my screenshot and description"
   git push
   ```
