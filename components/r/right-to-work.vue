<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoz3zibrm"/><path class="ddw0uq-1u"/><path class="gko6xgb5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:right-to-work" /></template>
<style>
.ddw0uq-1u {
  d: path("M8.75 8.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.eoz3zibrm {
  d: path("M4.5 2.5h15v19h-15Z");
}

.gko6xgb5f {
  d: path("M10.75 8.5a1.25 3.25 0 1 0 2.5 0a1.25 3.25 0 1 0-2.5 0ZM9 16.5l2 2l4-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
