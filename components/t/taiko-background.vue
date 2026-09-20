<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="h3q7jabtx"/><path class="m66666bkf"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:taiko-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h3q7jabtx {
  fill: var(--svg-color--e81899, #e81899);
  d: path("M24 0H0v24h24z");
}

.m66666bkf {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("m19.664 16.32l-2.742-3.65a1.75 1.75 0 0 0-1.208-.687a.34.34 0 0 1-.256-.165a.33.33 0 0 1-.018-.3c.189-.425.2-.918-.002-1.37l-1.855-4.151A1.73 1.73 0 0 0 12 4.982a1.73 1.73 0 0 0-1.583 1.015l-1.855 4.152c-.201.45-.19.944-.003 1.369a.33.33 0 0 1-.017.3a.34.34 0 0 1-.256.165c-.47.052-.91.29-1.208.686l-2.742 3.65a1.67 1.67 0 0 0-.105 1.852c.344.582 1.006.91 1.688.836l4.597-.502c.499-.054.93-.31 1.21-.682a.343.343 0 0 1 .548 0c.28.373.711.628 1.21.682l4.597.502a1.74 1.74 0 0 0 1.688-.836a1.67 1.67 0 0 0-.105-1.851M9.76 10.67l1.858-4.157a.419.419 0 0 1 .764 0l1.858 4.157a.42.42 0 0 1-.035.402a.44.44 0 0 1-.363.192h-3.685a.44.44 0 0 1-.363-.192a.42.42 0 0 1-.034-.402m.954 6.328a.43.43 0 0 1-.339.23l-4.601.502a.42.42 0 0 1-.408-.201a.4.4 0 0 1 .026-.447l2.745-3.654a.44.44 0 0 1 .372-.172a.43.43 0 0 1 .351.211l.003.005l1.838 3.12l.002.004a.42.42 0 0 1 .012.403zm1.663-1.41a.44.44 0 0 1-.756 0l-1.412-2.396a.42.42 0 0 1 0-.427a.44.44 0 0 1 .378-.215h2.823c.155 0 .3.08.378.214a.42.42 0 0 1 0 .427zm6.256 1.94a.42.42 0 0 1-.408.203l-4.601-.502a.43.43 0 0 1-.34-.23a.42.42 0 0 1 .012-.403l.003-.005l1.838-3.12l.003-.004a.438.438 0 0 1 .724-.04l2.744 3.656c.098.13.107.305.025.446");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
