# API Docs - v2.0.2

!!! Info "Tested Siddhi Core version: *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/">5.0.2</a>*"
    It could also support other Siddhi Core minor versions.

## Unitconversion

### MmTokm *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in megameters into kilometers.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:MmTokm(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from megameters into kilometers.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:MmTokm(1) 

```
<p style="word-wrap: break-word">The megameter value '1' is converted into kilometers as '1000.0' .</p>

### cmToft *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in centimeters into feet.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:cmToft(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from centimeters into feet.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:cmToft(100) 

```
<p style="word-wrap: break-word">The centimeters value '100' is converted into feet as '3.280' .</p>

### cmToin *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in centimeters into inches.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:cmToin(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from centimeters into inches.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:cmToin(100) 

```
<p style="word-wrap: break-word">Input centimeters value '100' is converted into inches as '39.37'.</p>

### cmTokm *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input value given in centimeters into kilometers.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:cmTokm(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from centimeters into kilometers.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:cmTokm(100) 

```
<p style="word-wrap: break-word">The centimeters value '100' is converted into kilometers as '0.001'.</p>

### cmTom *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in centimeters into meters.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:cmTom(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from centimeters into meters.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:cmTom(100) 

```
<p style="word-wrap: break-word">The centimeters value '100' is converted into meters as '1.0' .</p>

### cmTomi *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in centimeters into miles.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:cmTomi(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from centimeters into miles.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:cmTomi(10000) 

```
<p style="word-wrap: break-word">The centimeters value '10000' is converted into miles as '0.062' .</p>

### cmTomm *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in centimeters into millimeters.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:cmTomm(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from centimeters into millimeters.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:cmTomm(1) 

```
<p style="word-wrap: break-word">The centimeter value '1' is converted into millimeters as '10.0' .</p>

### cmTonm *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in centimeters into nanometers.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:cmTonm(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from centimeters into nanometers.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:cmTonm(1) 

```
<p style="word-wrap: break-word">The centimeter value '1' is converted into nanometers as '10000000' .</p>

### cmToum *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input in centimeters into micrometers.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:cmToum(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from centimeters into micrometers.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:cmToum(100) 

```
<p style="word-wrap: break-word">The centimeters value '100' is converted into micrometers as '1000000.0' .</p>

### cmToyd *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in centimeters into yards.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:cmToyd(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from centimeters into yards.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:cmToyd(1) 

```
<p style="word-wrap: break-word">The centimeter value '1' is converted into yards as '0.01' .</p>

### dToh *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in days into hours.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:dToh(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from days into hours.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:dToh(1) 

```
<p style="word-wrap: break-word">The day value '1' is converted into hours as '24.0'.</p>

### gTokg *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in grams into kilograms.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:gTokg(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from grams into kilograms.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:gTokg(1000) 

```
<p style="word-wrap: break-word">The grams value '1000' is converted into kilogram as '1.0' .</p>

### gTomg *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in grams into milligrams.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:gTomg(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from grams into milligrams.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:gTomg(1) 

```
<p style="word-wrap: break-word">The gram value '1' is converted into milligrams as '1000.0' .</p>

### gToug *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in grams into micrograms.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:gToug(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from grams into micrograms.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:gToug(1) 

```
<p style="word-wrap: break-word">The gram value '1' is converted into micrograms as '1000000.0' .</p>

### hTom *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in hours into minutes.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:hTom(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from hours into minutes.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:hTom(1) 

```
<p style="word-wrap: break-word">The hour value '1' is converted into minutes as '60.0' .</p>

### hTos *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in hours into seconds.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:hTos(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from hours into seconds.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:hTos(1) 

```
<p style="word-wrap: break-word">The hour value '1' is converted into seconds as '3600.0'.</p>

### kgToLT *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilograms into imperial tons.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kgToLT(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilograms into imperial tons.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kgToLT(1000) 

```
<p style="word-wrap: break-word">The kilograms value '1000' is converted into imperial tons as '0.9842' .</p>

### kgToST *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilograms into US tons.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kgToST(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilograms into US tons.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kgToST(1000) 

```
<p style="word-wrap: break-word">The kilograms value '1000 is converted into US tons as '1.10' .</p>

### kgTog *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilograms into grams.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kgTog(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilograms into grams.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kgTog(1) 

```
<p style="word-wrap: break-word">The kilogram value '1' is converted into grams as '1000'.</p>

### kgTolb *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilograms into pounds.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kgTolb(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilograms into pounds.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kgTolb(1) 

```
<p style="word-wrap: break-word">The kilogram value '1' is converted into pounds as '2.2' .</p>

### kgTooz *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilograms into ounces.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kgTooz(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilograms into ounces.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kgTooz(1) 

```
<p style="word-wrap: break-word">The kilogram value '1' is converted into ounces as ' 35.274' .</p>

### kgTost *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilograms into imperial stones.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kgTost(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilograms into imperial stones.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kgTost(1) 

```
<p style="word-wrap: break-word">The kilogram value '1' is converted into imperial stones as '0.157' .</p>

### kgTot *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilograms into tonnes.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kgTot(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilograms into tonnes.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kgTot(1) 

```
<p style="word-wrap: break-word">The kilogram value '1' is converted into tonnes as '0.001' .</p>

### kmTocm *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilometers into centimeters.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kmTocm(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilometers into centimeters.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kmTocm(1) 

```
<p style="word-wrap: break-word">The kilometer value '1' is converted into centimeters as '100000.0' .</p>

### kmToft *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilometers into feet.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kmToft(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilometers into feet.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kmToft(1) 

```
<p style="word-wrap: break-word">The kilometer value '1' is converted into feet as '3280.8' .</p>

### kmToin *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilometers into inches.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kmToin(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilometers into inches.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kmToin(1) 

```
<p style="word-wrap: break-word">The kilometer value '1' is converted into inches as '39370.08' .</p>

### kmTom *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilometers into meters.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kmTom(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilometers into meters.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kmTom(1) 

```
<p style="word-wrap: break-word">The kilometer value '1' is converted into meters as '1000.0' .</p>

### kmTomi *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilometers into miles.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kmTomi(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilometers into miles.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kmTomi(1) 

```
<p style="word-wrap: break-word">The kilometer value '1' is converted into miles as '0.621' .</p>

### kmTomm *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilometers into millimeters.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kmTomm(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilometers into millimeters.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kmTomm(1) 

```
<p style="word-wrap: break-word">The kilometer value '1' is converted into millimeters as '1000000.0' .</p>

### kmTonm *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilometers into nanometers.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kmTonm(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilometers into nanometers.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kmTonm(1) 

```
<p style="word-wrap: break-word">The kilometer value '1' is converted into nanometers as '1000000000000.0' .</p>

### kmToum *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilometers into micrometers.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kmToum(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilometers into micrometers.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kmToum(1) 

```
<p style="word-wrap: break-word">The kilometer value '1' is converted into micrometers as '1000000000.0' .</p>

### kmToyd *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in kilometers into yards.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:kmToyd(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from kilometers into yards.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:kmToyd(1) 

```
<p style="word-wrap: break-word">The kilometer value '1' is converted into yards as '1093.6' .</p>

### lTom3 *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in liters into cubic meters.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:lTom3(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from liters into cubic meters.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:lTom3(1000) 

```
<p style="word-wrap: break-word">The liters value '1000' is converted into cubic meters as '1' .</p>

### lToml *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in liters into milliliters.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:lToml(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from liters into milliliters.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:lToml(1) 

```
<p style="word-wrap: break-word">The liter value '1' is converted into milliliters as '1000.0' .</p>

### m3Tol *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in cubic meters into liters.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:m3Tol(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from meters into liters.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:m3Tol(1) 

```
<p style="word-wrap: break-word">The cubic meter value '1' is converted into liters as '1000.0' .</p>

### mTocm *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in meters into centimeters.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:mTocm(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from meters into centimeters.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:mTocm(1) 

```
<p style="word-wrap: break-word">The meter value '1' is converted to centimeters as '100.0' .</p>

### mToft *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in meters into feet.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:mToft(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from meters into feet.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:mToft(1) 

```
<p style="word-wrap: break-word">The meter value '1' is converted into feet as '3.280' .</p>

### mTomm *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in meters into millimeters.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:mTomm(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from meters into millimeters.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:mTomm(1) 

```
<p style="word-wrap: break-word">The meter value '1' is converted into millimeters as '1000.0' .</p>

### mTos *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in minutes into seconds.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:mTos(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from minutes into seconds.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:mTos(1) 

```
<p style="word-wrap: break-word">The minute value '1' is converted into seconds as '60.0' .</p>

### mToyd *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in meters into yards.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:mToyd(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from meters into yards.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:mToyd(1) 

```
<p style="word-wrap: break-word">The meter value '1' is converted into yards as '1.093' .</p>

### miTokm *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in miles into kilometers.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:miTokm(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from miles into kilometers.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:miTokm(1) 

```
<p style="word-wrap: break-word">The mile value '1' is converted into kilometers as '1.6' .</p>

### mlTol *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in milliliters into liters.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:mlTol(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from milliliters into liters.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:mlTol(1000) 

```
<p style="word-wrap: break-word">The milliliters value '1000' is converted into liters as '1'.</p>

### sToms *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in seconds into milliseconds.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:sToms(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from seconds into milliseconds.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:sToms(1) 

```
<p style="word-wrap: break-word">The second value '1' is converted into milliseconds as '1000.0' .</p>

### sTons *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in seconds into nanoseconds.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:sTons(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from seconds into nanoseconds.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:sTons(1) 

```
<p style="word-wrap: break-word">The second value '1' is converted into nanoseconds as '1000000000.0' .</p>

### sTous *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in seconds into microseconds.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:sTous(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from seconds into microseconds.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:sTous(1) 

```
<p style="word-wrap: break-word">The second value '1' is converted into microseconds as '1000000.0' .</p>

### tTog *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in tonnes into grams.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:tTog(<INT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from Tonnes into grams.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:tTog(1) 

```
<p style="word-wrap: break-word">The tonne value '1' is converted into grams as '1000000.0' .</p>

### tTokg *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the input given in tonnes into kilograms.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:tTokg(<INT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from tonnes into kilograms.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:tTokg(inValue) 

```
<p style="word-wrap: break-word">The tonne value is converted into kilograms as '1000.0' .</p>

### yTod *<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">(Function)</a>*
<p style="word-wrap: break-word">This converts the given input in years into days.</p>
<span id="syntax" class="md-typeset" style="display: block; font-weight: bold;">Syntax</span>

```
<DOUBLE> unitconversion:yTod(<INT|LONG|FLOAT|DOUBLE> p1)
```

<span id="query-parameters" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">QUERY PARAMETERS</span>
<table>
    <tr>
        <th>Name</th>
        <th style="min-width: 20em">Description</th>
        <th>Default Value</th>
        <th>Possible Data Types</th>
        <th>Optional</th>
        <th>Dynamic</th>
    </tr>
    <tr>
        <td style="vertical-align: top">p1</td>
        <td style="vertical-align: top; word-wrap: break-word">The value that needs to be converted from years into days.</td>
        <td style="vertical-align: top"></td>
        <td style="vertical-align: top">INT<br>LONG<br>FLOAT<br>DOUBLE</td>
        <td style="vertical-align: top">No</td>
        <td style="vertical-align: top">Yes</td>
    </tr>
</table>

<span id="examples" class="md-typeset" style="display: block; font-weight: bold;">Examples</span>
<span id="example-1" class="md-typeset" style="display: block; color: rgba(0, 0, 0, 0.54); font-size: 12.8px; font-weight: bold;">EXAMPLE 1</span>
```
unitconversion:yTod(1) 

```
<p style="word-wrap: break-word">The year value '1' is converted into days as '365.2525' .</p>

