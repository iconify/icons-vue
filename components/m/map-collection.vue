<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hkoqnyrzh"/><path class="q4kykgc9i"/><path class="tmucf2bze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-collection" /></template>
<style>
.hkoqnyrzh {
  d: path("m2.5 10l4.25-1.5l4.5 1.5l4.25-1.5V20l-4.25 1.5l-4.5-1.5l-4.25 1.5Zm4.25-1.5V20m4.5-10v11.5");
}

.q4kykgc9i {
  d: path("m5.5 7l4.25-1.5l4.5 1.5l4.25-1.5V17l-3 1");
}

.tmucf2bze {
  d: path("m8.5 4l4.25-1.5l4.5 1.5l4.25-1.5V14l-3 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
