<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hji3l8mox"/><path class="nahplibqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:muscle-sharp" /></template>
<style>
.hji3l8mox {
  d: path("M3.25 19.5c0-3 1.5-5.75 4-7.25L10 5.5l.7-1.75h4.05l1.488-.016l.4 2.95l-1.488.016l-2.15.8l-1.25 4.25c1.75-1.5 4-2 6-1.25c2.25.85 3 3.25 2.25 5.5c-.9 2.75-3.6 4.25-6.5 4.25H3.25v-1.5Z");
}

.nahplibqz {
  d: path("m11.5 16l2.438-2.031L16.5 15.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
