<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="npwjmubbf"/><path class="mj0cu8b4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tennis-scoreboard" /></template>
<style>
.mj0cu8b4i {
  d: path("M5.25 6h4v8h-4Zm9.5 0h4v8h-4Z");
}

.npwjmubbf {
  d: path("M2.5 3h19v14h-19ZM7 17v4m10-4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
