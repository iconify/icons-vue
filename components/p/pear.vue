<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="axrcz2bsw"/><path class="nyt8_lbii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pear" /></template>
<style>
.axrcz2bsw {
  d: path("M12 8c-1.75 0-2.75.5-3 2c-.25 1.75-1.25 2.5-2.25 3.75c-.9 1.1-1.5 2.4-1.5 3.9c0 2.75 2.5 3.6 6.75 3.6s6.75-.85 6.75-3.6c0-1.5-.6-2.8-1.5-3.9c-1-1.25-2-2-2.25-3.75c-.25-1.5-1.25-2-3-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nyt8_lbii {
  d: path("M12 8c0-2-.25-3.4-1-4.25m1 1.5c1-2 3-2.75 5.5-2.25c-.9 2.5-2.9 3.25-5.5 2.25M8.5 17.5c0-1 .4-1.9 1.1-2.6");
}

</style>
