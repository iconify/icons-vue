<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9myj-bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:time-signature" /></template>
<style>
.t9myj-bqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3.75c.8-.65 1.9-1 3.25-1c1.75 0 3 .75 3 1.9s-1.3 1.85-3 1.85c1.9 0 3.25.75 3.25 1.95c0 1.25-1.35 2.05-3.25 2.05c-1.3 0-2.45-.35-3.25-1m5.25 11.75V13.5L8 19h8.5");
}

</style>
