<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGmfC4feVg)" class="r4i437pya"/><path class="l0zjz4_fy"/></g><defs><linearGradient id="SVGmfC4feVg" x1="4" x2="20" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="vh9-4hb8q"/><stop offset="1" class="r9zkbkbnp"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:myst-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l0zjz4_fy {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.952 13.167l-5.188-5.121a.18.18 0 0 0-.24 0l-2.548 2.505L9.48 8.086a.17.17 0 0 0-.242 0l-.78.755l-2.864 2.772l-.626.607l-.92.885a.16.16 0 0 0-.048.123a.2.2 0 0 0 .047.122l2.588 2.554c.068.067.18.067.241 0l2.486-2.45l2.517 2.485c.068.067.18.067.241 0l2.492-2.46l2.505 2.474a.17.17 0 0 0 .124.047a.18.18 0 0 0 .124-.047l2.588-2.554a.16.16 0 0 0 .047-.122c0-.05-.015-.084-.048-.11m-.465.212L18 12.839l-.683-1.453l.394.056l1.87 1.846zm-.84.83l-.442-.932l1.015.368zm-10.244-3.36l-2.097.558l2.097-2.035zM5.8 11.893l1.47-.389l-.096 1.634l-1.788-.838zm1.824-.482l.261-.066l.697 1.056l-1.09 1.192zm1.19.72l-.584-.885l.332-.087l.835.34zm-.067-1.266v-.618l1.988.163l.497 1.472zm1.682 1.913l.712.43l.118 1.64l-1.006-.987zm.968.186l-.903-.551l.068-.43l.85.348q.029.024.067.027l.856.354l.359 1.047zm1.288-.302l.932-.476l-.682 1.2zm1.291-1.033l-.862.441l.206-1.443l1.2.723zm.903-.464l-1.609-.967l-.282-.171l.423-.416l1.83.587l.173.694zm.877-.334l-.427-1.75l1.988 1.961zm.014.342l.365.047l.394 3.663l-1.05-1.036zm.712.102l.435.06l.62 1.321l-.758 1.391zm-1.844-2.868l.214.212l.292 1.193l-1.456-.465zm-2.544 2.513l.65-.641l.256.157l-.262 1.826l-.268.136l-.826-.334l-.677-2.008l.883.87a.19.19 0 0 0 .244-.006M9.353 8.455l1.07 1.054l.186.551l-1.862-.156v-.866zm-4.235 4.099l2.03.946l-.057.9l-1.814-.314l-.862-.85zm1.635 2.996l-1.056-1.042l1.365.238l-.036.525zm2.482-2.453L7.4 14.908l.047-.775l.006-.006l2.276-2.485l.503.203l-.103.628l-.18 1.088l-.47-.464a.173.173 0 0 0-.244 0m2.768 2.487l-.374-.368l-.124-1.791l1.365.83l.124.354zm2.614-2.507a.2.2 0 0 0-.123.046l-1.235 1.22l-.18-.527l1.097-1.92l1.235-.628l-.246 2.267l-.421-.415a.2.2 0 0 0-.127-.043m2.624 2.52l-.333-.329l-.068-.627l.877-1.608l.67 1.431z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.r9zkbkbnp {
  stop-color: var(--svg-color--302361, #302361);
}

.vh9-4hb8q {
  stop-color: var(--svg-color--c31f5d, #c31f5d);
}

</style>
