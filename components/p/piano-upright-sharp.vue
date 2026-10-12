<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsni-ccqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:piano-upright-sharp" /></template>
<style>
.bsni-ccqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 17.5V2.75h5.5V5.5c0 3.5 2.25 5 5.25 6.75c2.5 1.45 3.75 3.25 3.75 5.25Zm-1 0h16.5v3.75H3.75zm4 0v3.75M12 17.5v3.75m4.25-3.75v3.75");
}

</style>
