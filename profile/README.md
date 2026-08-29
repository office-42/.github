<div align="center">

# 🏢 office-42

**A word processor, a spreadsheet and a mathematics notebook — written from
scratch in C on GTK 4, Pango and Cairo.**

</div>

### 🧰 The three programs

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>📄 <a href="https://github.com/office-42/word42">word42</a></h3>
      <p><b>A word processor</b></p>
      <p>A ruler, a page, and the shape of the classics: styles, tables, footnotes, columns, headers and footers, mail merge, spelling, an outline view. Reads and writes <code>.docx</code>, <code>.doc</code>, <code>.odt</code>, <code>.rtf</code>, HTML and Markdown, prints, and exports PDF with real text in it.</p>
      <p><a href="https://github.com/office-42/word42"><b>View Repository &rarr;</b></a></p>
    </td>
    <td width="33%" valign="top">
      <h3>📊 <a href="https://github.com/office-42/office42">office42</a></h3>
      <p><b>A spreadsheet</b></p>
      <p>A grid, a formula bar and sheet tabs. 561 functions, thirteen kinds of chart, pivot tables, form controls and a recalculation that knows what depends on what. Reads and writes <code>.gnumeric</code>, <code>.xlsx</code>, <code>.xls</code>, <code>.ods</code>, CSV and PDF. Python is its macro language, and a book can carry a SQLite database inside it.</p>
      <p><a href="https://github.com/office-42/office42"><b>View Repository &rarr;</b></a></p>
    </td>
    <td width="33%" valign="top">
      <h3>📐 <a href="https://github.com/office-42/math42">math42</a></h3>
      <p><b>A mathematics notebook</b></p>
      <p>Type an expression and the answer is set as mathematics: fractions stacked, roots under a radical, matrices in brackets, graphs drawn. It speaks two languages — <code>Sin[Pi/2]</code> and <code>sin(pi/2)</code> both work — and covers the mathematics an engineering degree teaches.</p>
      <p><a href="https://github.com/office-42/math42"><b>View Repository &rarr;</b></a></p>
    </td>
  </tr>
</table>

The showcase, with pictures: **[office-42.github.io](https://office-42.github.io)**

---

### 🧩 The same principles, in all three

* **C, and not much of it.** GTK 4, Pango, Cairo and GLib; no framework, no
  bindings, no generated code, and the engine of each one builds without the
  user interface.
* **The shape of the classics.** A menu bar and toolbars that stay where you
  left them; no ribbon, no cloud, no account.
* **Honest about what it cannot do.** Each ships a review of itself that says
  where it falls short — see office42's
  [PARITY.md](https://github.com/office-42/office42/blob/main/docs/PARITY.md).
* **Free software**, GPL-3.0-or-later, building on Linux, macOS and Windows.

---

### 🚀 Quick start

```bash
git clone https://github.com/office-42/office42.git
cd office42
meson setup builddir && meson compile -C builddir
./builddir/src/office42            # the window
./builddir/src/office42-calc       # the engine, from a terminal
```

`word42` and `math42` build the same way.

---

These programs are independent. They are not affiliated with, endorsed by or
derived from Microsoft, The Document Foundation, the GNOME Foundation or
Wolfram Research, and carry no code or artwork of theirs. The names used to
say what a file format is, or what a program resembles, belong to their
owners.
