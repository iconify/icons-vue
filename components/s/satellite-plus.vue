<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xq1whjfip"/><path class="xjaee884v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:satellite-plus" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xjaee884v {
  d: path("m3.868 16.596l4.243-4.242l3.535 3.535l-4.242 4.243Zm8.486-8.485l4.242-4.243l3.536 3.536l-4.243 4.242ZM5.636 5.636a3 3 0 0 1 4.243 4.243M18 15v6m-3-3h6");
}

.xq1whjfip {
  d: path("m12.213 16.03l-.213.213L7.757 12L12 7.757L16.243 12l-.211.211m-.849.849l-2.121 2.121");
}

</style>
