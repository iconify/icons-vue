<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mnb31-y4i"/><path class="u81qlbcma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:monitor-input" /></template>
<style>
.mnb31-y4i {
  d: path("M2.5 3.5h19v13h-19Zm9.5 13v4m-4 0h8M7.5 10h6");
}

.u81qlbcma {
  d: path("M11.5 7.5L14 10l-2.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
