<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qk4du0kcf"/><path class="l_5b1nhzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:satellite-off" /></template>
<style>
.l_5b1nhzl {
  d: path("m3.868 16.596l4.243-4.242l3.535 3.535l-4.242 4.243Zm8.486-8.485l4.242-4.243l3.536 3.536l-4.243 4.242ZM8.907 4.987q.55.228.971.65q.428.427.657.987M3.5 3.5l17 17");
}

.qk4du0kcf {
  d: path("m12.143 16.1l-.143.143L7.757 12l.141-.141m3.96-3.96L12 7.757L16.243 12l-.141.141");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
