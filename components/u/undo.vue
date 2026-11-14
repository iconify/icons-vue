<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vzmnvky3g"/><path class="bfwiu2w4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:undo" /></template>
<style>
.bfwiu2w4e {
  d: path("m8.5 5.5l-4 4l4 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vzmnvky3g {
  d: path("M4.5 9.5h10a5 5 0 0 1 0 10H9");
}

</style>
