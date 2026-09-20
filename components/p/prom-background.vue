<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGO3IwDcVS)" class="r4i437pya"/><path class="nf0s8ob7l"/></g><defs><linearGradient id="SVGO3IwDcVS" x1="21.827" x2="5.298" y1="5.221" y2="21.75" gradientUnits="userSpaceOnUse"><stop class="uj9o2mbff"/><stop offset="1" class="st-qj8kka"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:prom-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nf0s8ob7l {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.38 5.172l-9.845 6.953a5.87 5.87 0 0 1-.893-3.132C6.643 5.682 9.356 3 12.708 3a6.07 6.07 0 0 1 4.673 2.172m.119 5.09a5.9 5.9 0 0 0-.892-3.133l-4.911 3.465l-4.936 3.48l-.261.186l.012 6.74s6.492-4.33 8.538-5.921c1.522-1.186 2.45-2.847 2.45-4.817");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.st-qj8kka {
  stop-color: var(--svg-color--ee448a, #ee448a);
}

.uj9o2mbff {
  stop-color: var(--svg-color--e2d177, #e2d177);
}

</style>
