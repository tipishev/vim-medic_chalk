# Foreword

I have forked this from [Tpope's Vividchalk](https://github.com/tpope/vim-vividchalk)
and slightly modified it.

All credit goes to him. Check him out. He has many great Vim plugins.

<br />

## Installation

```vimL
call plug#begin()
  Plug 'ParamagicDev/vim-medic-chalk'
call plug#end()

colorscheme medic_chalk
```

The table below contains a subset of VividChalks’s palette. You can use a color picker or copy/paste these values:

<table>
    <thead>
        <tr>
            <th style="width: 12rem;">Intensity</th>
            <th style="width: 22rem">Normal</th>
            <th style="width: 12rem">Intensity</th>
            <th style="width: 22rem">Bright</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="middle" style="min-width: 1rem;">0</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#000000</code>
              <div style="display: inline-block; background: #000000; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
            <td align="middle">8</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#808080</code>
              <div style="display: inline-block; background: #808080; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
        </tr>
        <tr>
            <td align="middle">1</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#FFA500</code>
              <div style="display: inline-block; background: #FFA500; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
            <td align="middle">9</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#FF6600</code>
              <div style="display: inline-block; background: #FF6600; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
        </tr>
        <tr>
            <td align="middle">2</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#66FF00</code>
              <div style="display: inline-block; background: #66FF00; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
            <td align="middle">10</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#99CC99</code>
              <div style="display: inline-block; background: #99CC99; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
        </tr>
        <tr>
            <td align="middle">3</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#FFCC00</code>
              <div style="display: inline-block; background: #FFCC00; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
            <td align="middle">11</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#FFEE98</code>
              <div style="display: inline-block; background: #FFEE98; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
        </tr>
        <tr>
            <td align="middle">4</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#5F87AF</code>
              <div style="display: inline-block; background: #5F87AF; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
            <td align="middle">12</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#33C9C9</code>
              <div style="display: inline-block; background: #33C9C9; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
        </tr>
        <tr>
            <td align="middle">5</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#9933CC</code>
              <div style="display: inline-block; background: #9933CC; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
            <td align="middle">13</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#AA1BF2</code>
              <div style="display: inline-block; background: #AA1BF2; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
        </tr>
        <tr>
            <td align="middle">6</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#88B5C3</code>
              <div style="display: inline-block; background: #88B5C3; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
            <td align="middle">14</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#AABBEE</code>
              <div style="display: inline-block; background: #AABBEE; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
        </tr>
        <tr>
            <td align="middle">7</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#FFFFFF</code>
              <div style="display: inline-block; background: #FFFFFF; border: 1px solid black; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
            <td align="middle">15</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#A9A9A9</code>
              <div style="display: inline-block; background: #A9A9A9; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
        </tr>
        <tr>
            <td align="middle">Foreground Color</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#FFFFFF</code>
              <div style="display: inline-block; background: #FFFFFF; border: 1px solid black; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
            <td align="middle">Background color</td>
            <td style="display: flex; justify-content: center; align-items: center;">
              <code>#000000</code>
              <div style="display: inline-block; background: #000000; margin-left: 0.75rem; min-width: 3rem; width: 70%; max-width: 9rem; height: 2.5rem;"></div>
            </td>
        </tr>
    </tbody>
</table>

The table above is from [Romainl's Apprentice](https://github.com/romainl/Apprentice)

