<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iavtsfbxs"/><path class="f3rj04b6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:security-dye-pack" /></template>
<style>
.f3rj04b6r {
  d: path("M10.5 4h3v11h-3ZM5 9.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm13 4.75C19.75 16.5 21 18 21 19a3 3 0 0 1-6 0c0-1 1.25-2.5 3-4.75Z");
}

.iavtsfbxs {
  d: path("M14 15H2.5V4h19v10.3m-18 3.45h9m-8 2.75h7.9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
