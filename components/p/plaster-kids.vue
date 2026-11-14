<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ggyj2acbm"/><path class="gqhkf0wts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plaster-kids" /></template>
<style>
.ggyj2acbm {
  d: path("M4 7.5h16A1.5 1.5 0 0 1 21.5 9v6a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 15V9A1.5 1.5 0 0 1 4 7.5Z");
}

.gqhkf0wts {
  d: path("M8.5 7.5c-1 2.5-1 6.5 0 9m7-9c1 2.5 1 6.5 0 9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
