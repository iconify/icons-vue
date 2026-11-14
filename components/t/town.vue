<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tefboslho"/><path class="aiii4rbwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:town" /></template>
<style>
.aiii4rbwo {
  d: path("M6 12h3v3H6Zm9.5 9.5v-4h3v4");
}

.tefboslho {
  d: path("m2.5 9l5-5.5l5 5.5v12.5h-10Zm10 4L17 8.5l4.5 4.5v8.5h-9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
