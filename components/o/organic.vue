<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yjjc8cctt"/><path class="hvjyoqu3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:organic" /></template>
<style>
.hvjyoqu3q {
  d: path("M8.75 15.25c0-4.25 2.25-6.5 6.5-6.5c0 4.25-2.25 6.5-6.5 6.5Zm0 0l3.5-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yjjc8cctt {
  d: path("M19.75 12a3.25 3.25 0 0 1-2.25 5.5a3.25 3.25 0 0 1-5.5 2.25a3.25 3.25 0 0 1-5.5-2.25A3.25 3.25 0 0 1 4.25 12A3.25 3.25 0 0 1 6.5 6.5A3.25 3.25 0 0 1 12 4.25a3.25 3.25 0 0 1 5.5 2.25a3.25 3.25 0 0 1 2.25 5.5Z");
}

</style>
