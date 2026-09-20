<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="skm5aab5n"/><path clip-rule="evenodd" class="x73xvfbpm"/><path class="oph83rbtg"/><path class="a_dpd2n-d"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nbt-background" /></template>
<style>
.a_dpd2n-d {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.411 8.706a1.176 1.176 0 1 0 0-2.352a1.176 1.176 0 0 0 0 2.352m-1.176 7.058h7.53v.94h-7.53z");
}

.ft5dv1b6b {
  fill: none;
}

.oph83rbtg {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.764 13.76c0 .584-.55 1.064-1.176 1.064s-1.177-.48-1.177-1.063v-3.643c0-.706-.41-1.412-1.355-1.412h-.113c-.946 0-1.355.706-1.355 1.412v3.643c0 .583-.55 1.063-1.177 1.063c-.626 0-1.176-.48-1.176-1.063V9.648c0-1.878 1.694-3.294 3.69-3.294h.112c1.977 0 3.727 1.425 3.727 3.294z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.skm5aab5n {
  fill: var(--svg-color--2a1f63, #2a1f63);
  d: path("M24 0H0v24h24z");
}

.x73xvfbpm {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-.941 0a7.06 7.06 0 1 1-14.12 0a7.06 7.06 0 0 1 14.12 0");
}

</style>
