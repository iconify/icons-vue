<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="he8nlt9wg"/><path class="ni1ybj4mz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:media-converter" /></template>
<style>
.he8nlt9wg {
  d: path("M2.5 11h19v9h-19Z");
}

.ni1ybj4mz {
  d: path("M5.5 13.75h4v3.5h-4Zm9 0h4v3.5h-4ZM5 5.5h14m-11.5-2L5 5.5l2.5 2m9-4l2.5 2l-2.5 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
