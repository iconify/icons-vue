<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pb2fk8bad"/><path class="ohq03ubuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:quote-saved" /></template>
<style>
.ohq03ubuw {
  d: path("M16 15h4v6l-2-1.5l-2 1.5Z");
}

.pb2fk8bad {
  d: path("M5 3h14v9.25h-6.75V20l-3.5-1.75l-3.75 2Zm3.5 3.5h7m-7 3h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
