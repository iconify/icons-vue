<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jm0ppvbro"/><path class="zzd3robdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spaghetti-sharp" /></template>
<style>
.jm0ppvbro {
  d: path("M2.75 17h18.5c-.5 2.5-3 4.25-6 4.25h-6.5c-3 0-5.5-1.75-6-4.25ZM11 6.5a4.75 3.5 0 1 1 0 7a4.75 3.5 0 1 1 0-7Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zzd3robdi {
  d: path("M6.25 9.75c3 1 6.5 1 9.5 0m-6.5 3.65c-.75 1.25.75 2.35 0 3.6m4.8-9.68l4.57-4.57");
}

</style>
