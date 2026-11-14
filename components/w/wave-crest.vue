<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgou8tk8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wave-crest" /></template>
<style>
.hgou8tk8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19c4-1 5.5-5 6.5-8.5c1.5-5 6.5-7 10-4.75c2 1.25 1.5 4.25-1 4.5C16.75 10.5 16 9 17 8M3 19h18");
}

</style>
