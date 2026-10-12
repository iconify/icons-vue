<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j4v5gbc7b"/><path class="a464gbbma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:viking-helmet" /></template>
<style>
.a464gbbma {
  d: path("M6.2 11.9C4 11.25 2.75 9.25 2.75 5.75C4 8 6.25 9.25 8.8 9.75Zm11.6 0c2.2-.65 3.45-2.65 3.45-6.15c-1.25 2.25-3.5 3.5-6.05 4Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j4v5gbc7b {
  d: path("M4.75 16.25a7.25 7.25 0 0 1 14.5 0v1.5c0 .4-.35.75-.75.75h-5.25v2c0 .4-.35.75-.75.75h-1c-.4 0-.75-.35-.75-.75v-2H5.5c-.4 0-.75-.35-.75-.75Zm1-1h12.5M12 10v5.25");
}

</style>
