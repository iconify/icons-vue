<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oko11v-0c"/><path class="zu8oad3xs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pop-out" /></template>
<style>
.oko11v-0c {
  d: path("M7 8H4.5a2 2 0 0 0-2 2v8.5a2 2 0 0 0 2 2H13a2 2 0 0 0 2-2V15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zu8oad3xs {
  d: path("M10 3h11.5v9H10ZM5.5 17.5l3.25-3.25m-2.5 0h2.5v2.5");
}

</style>
