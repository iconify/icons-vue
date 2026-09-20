<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka_tr2vfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:piggy-bank-outline-thin" /></template>
<style>
.ka_tr2vfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 12.5a7 7 0 1 1 14 0 7 7 0 1 1 -14 0m12 -2h5v4h-5M7.5 19v3m7 -3v3m-5 -19v2.5m6 2.5 2 -2 2 2");
}

</style>
