<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl2fjrkyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-direction-ltr-round" /></template>
<style>
.kl2fjrkyq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 3h6m-5 0v8m4-8v8m-5-8a3 3 0 0 0 0 6h1m6 12l3-3l-3-3m3 3H3");
}

</style>
