<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l678ypbwk"/><path class="mwz2inb5v"/><path class="x1f4lc3zb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:separator-vertical-broken" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l678ypbwk {
  d: path("M4.5 10.5L3 12L9 18M7.5 7.5L9 6");
}

.mwz2inb5v {
  d: path("M19.5 10.5L21 12L15 18M16.5 7.5L15 6");
}

.x1f4lc3zb {
  d: path("M12 2L12 22");
}

</style>
