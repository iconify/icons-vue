<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zuzmdubdg"/><path class="vox1eebmj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:metal-detector-sharp" /></template>
<style>
.vox1eebmj {
  d: path("M10 7.5v-2h4V10h-4V8Zm0 5.75h4v8h-4zm9.75-8a5 5 0 0 1 0 5.5m-15.5-5.5a5 5 0 0 0 0 5.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zuzmdubdg {
  d: path("M7.25 2.75h9.5v10.5h-9.5z");
}

</style>
