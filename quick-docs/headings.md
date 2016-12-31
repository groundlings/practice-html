# Headings

## Background
Heading content defines the header of a section (whether explicitly marked
 up using sectioning content elements, or implied by the heading content itself).

## Code
```
<body>
  <h1>1st level heading</h1>
  <h2>2nd level heading</h2>
  <h3>3nd level heading</h3>
  <h4>4th level heading</h4>
  <h5>5th level heading</h5>
  <h6>6th level heading</h6>
</body>
```
Is equivalent to
```
<body>
<h1>1st level heading</h1>
  <section>
  <h2>2nd level heading</h2>  
    <section>
    <h3>3nd level heading</h3>
      <section>
      <h4>4th level heading</h4>
        <section>
        <h5>5th level heading</h5>
          <section>
          <h6>6th level heading</h6>
          </section>
        </section>
      </section>
    </section>
  </section>
</body>
```
