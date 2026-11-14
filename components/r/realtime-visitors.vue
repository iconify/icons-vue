<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7ba38n3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:realtime-visitors" /></template>
<style>
.g7ba38n3n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5c0-3.25 2.5-5.5 6-5.5c1.622 0 3.029.483 4.072 1.325M5 8.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm8.5-1.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm3 5.5c1.337 0 2.498.353 3.377.954M18 18.5h.01m2.288-1.928a3 3 0 0 1 0 3.856m-4.596 0a3 3 0 0 1 0-3.856");
}

</style>
