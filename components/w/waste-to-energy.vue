<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uipp9wbld"/><path class="esf8f2b8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:waste-to-energy" /></template>
<style>
.esf8f2b8y {
  d: path("m17.447 15.013l-1.737 2.085a.703.703 0 0 0 .54 1.152a1.3 1.3 0 0 1 1.288 1.485L17.5 20a.476.476 0 0 0 .845.363l1.726-2.186A.727.727 0 0 0 19.5 17a1.287 1.287 0 0 1-1.272-1.483l.022-.142a.457.457 0 0 0-.803-.362");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uipp9wbld {
  d: path("M14.362 20.5H3v-9l5-3v3l5-3v3h3.5v-8h4v9.838M6.5 15.5h2m3 0h1.9");
}

</style>
