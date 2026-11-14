<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lhrem1bfc"/><path class="ctkyn9_8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tampons-box" /></template>
<style>
.ctkyn9_8i {
  d: path("M10.5 6.5a1.5 1.5 0 0 0 3 0m-5.75 5h8.5V17h-8.5Z");
}

.lhrem1bfc {
  d: path("M5 2.5h14v19H5Zm0 4h14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
