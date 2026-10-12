<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qacvtk24h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pray-sharp" /></template>
<style>
.qacvtk24h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3c1.75 1.75 4 5.5 4 10.5a4 4 0 0 1-8 0c0-5 2.25-8.75 4-10.5Zm0 2v12.5m-2.5 3h5");
}

</style>
