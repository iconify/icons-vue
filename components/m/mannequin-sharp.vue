<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqfydbcol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mannequin-sharp" /></template>
<style>
.iqfydbcol {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 2.75h2.5V5.5h-2.5zM8 5.5h9l.71.71l.08.08l.71.71l-.5.86l-.75 1.28q-.5.86-1.17 1.6l-.91 1.02l-.67.74l.58.81l1.34 1.88l.58.81H7l.58-.81l1.34-1.88l.58-.81l-.67-.74l-.91-1.02q-.67-.74-1.17-1.6L6 7.86L5.5 7l.71-.71l.08-.08L7 5.5zm4 11v3.25m-3.25 1.5l3.25-1.5l3.25 1.5");
}

</style>
