<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l9pb4jh3n"/><circle class="yzxt5rhfr"/><circle class="yi78wl5tr"/><path class="c3hdb9bdc"/><path class="zlbyb8b6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pallete-2-broken" /></template>
<style>
.c3hdb9bdc {
  d: path("M11.085 6.99976C11.085 7.82818 10.4134 8.49976 9.58496 8.49976C8.75653 8.49976 8.08496 7.82818 8.08496 6.99976C8.08496 6.17133 8.75653 5.49976 9.58496 5.49976C10.4134 5.49976 11.085 6.17133 11.085 6.99976Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l9pb4jh3n {
  d: path("M7 3.34132C8.47087 2.48824 10.1786 2 12 2C17.5228 2 22 6.48884 22 12.0261C22 20.178 13.8385 14.4192 12.2619 16.9268C11.8674 17.5541 12.2938 18.3364 12.8168 18.8607C13.4703 19.5159 13.4703 20.5781 12.8168 21.2333C12.2938 21.7576 11.5816 22.0709 10.8468 21.9863C5.86713 21.413 2 17.1723 2 12.0261C2 10.1945 2.48985 8.47765 3.34537 7");
}

.yi78wl5tr {
  cx: 6.5px;
  cy: 11.5px;
  r: 1.5px;
}

.yzxt5rhfr {
  cx: 17.5px;
  cy: 11.5px;
  r: 1.5px;
}

.zlbyb8b6o {
  d: path("M16 7C16 7.82843 15.3284 8.5 14.5 8.5C13.6716 8.5 13 7.82843 13 7C13 6.17157 13.6716 5.5 14.5 5.5C15.3284 5.5 16 6.17157 16 7Z");
}

</style>
