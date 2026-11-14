<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nzrhd1b-j"/><path class="ob30dxblc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:topiary-ball" /></template>
<style>
.nzrhd1b-j {
  d: path("M6.25 8.25a5.75 5.75 0 1 0 11.5 0a5.75 5.75 0 1 0-11.5 0ZM12 14v2.5m-5.5 0h11l-1.25 5h-8.5Z");
}

.ob30dxblc {
  d: path("M9.25 7.25a3 3 0 0 1 2.25-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
