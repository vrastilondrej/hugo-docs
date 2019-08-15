---
title: Speciální třídy
type: docs
---

# Speciální třídy
## Přimo v konfiguračním souboru Tailwindu
### `.section`
Slouží k vertikálnímu odsazení sekcí

- tailwind moduly: `responsive`

{{< tabs "uniqueid" >}}

{{< tab "použití" >}}
{{< highlight html >}}
<section class="bg-primary-darker section-sm md:section-xl"> test</section>
{{< /highlight >}}
{{< /tab >}}

{{< tab "tailwind.config.js" >}}
{{< highlight js >}}
 '.section-3xl': {
     padding: '16rem 0',
 },
 '.section-2xl': {
     padding: '12rem 0',
 },
 '.section-xl': {
     padding: '8rem 0',
 },
 '.section-md': {
     padding: '4rem 0',
 },
 '.section-sm': {
     padding: '2rem 0',
 },
{{< /highlight >}}
{{< /tab >}}

{{< /tabs >}}

## V CSS souboru
### `.transition`

{{< tabs "uniqueid2" >}}

{{< tab "použití" >}}

{{< rawhtml >}}
<div class="transition bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 inline">
  Button
</div>
{{< /rawhtml >}}
{{< highlight html >}}
<div class="transition bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 inline">
  Button
</div>
{{< /highlight >}}
{{< /tab >}}

{{< tab "CSS" >}}
{{< highlight css >}}
.transition {
    transition: all 0.2s cubic-bezier(.77, .1, .05, 0.99);
}
{{< /highlight >}}
{{< /tab >}}

{{< /tabs >}}

