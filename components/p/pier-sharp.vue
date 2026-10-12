<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofqsl9klq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pier-sharp" /></template>
<style>
.ofqsl9klq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.5h18.5m-7.5 0v-3a3.75 3.75 0 0 1 7.5 0v3Zm3.75-6.75v-2.5M6 12.5v-3m-1 3V17m5-4.5V17m5-4.5V17m4.5-4.5V17M3 19.5c1.5 0 1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1");
}

</style>
