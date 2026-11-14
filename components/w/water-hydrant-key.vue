<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gue6m-kvl"/><path class="zpf4cxbii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-hydrant-key" /></template>
<style>
.gue6m-kvl {
  d: path("m16.529 3.747l3.173 2.306a1.75 1.75 0 0 1 .636 1.957l-1.212 3.73a1.75 1.75 0 0 1-1.665 1.21h-3.922a1.75 1.75 0 0 1-1.665-1.21l-1.212-3.73a1.75 1.75 0 0 1 .636-1.957l3.173-2.306a1.75 1.75 0 0 1 2.058 0M11.75 12.25L3.5 20.5m2.25-2.25l2 2m.5-4.5l1.5 1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zpf4cxbii {
  d: path("m16.382 7.141l.138.1a1.5 1.5 0 0 1 .545 1.677l-.053.164a1.5 1.5 0 0 1-1.426 1.036h-.172a1.5 1.5 0 0 1-1.426-1.036l-.053-.164a1.5 1.5 0 0 1 .545-1.677l.138-.1a1.5 1.5 0 0 1 1.764 0");
}

</style>
