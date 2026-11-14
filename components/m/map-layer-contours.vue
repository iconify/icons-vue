<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhzhk1kgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-layer-contours" /></template>
<style>
.lhzhk1kgw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 13q0-4.561 2.692-7.563Q7.799 2.25 12.5 2.25q9.25 0 9.25 7.75q0 11.75-7.25 11.75q-12.25 0-12.25-8.75m7.204-6.292Q7.5 8.357 7.5 11q0 5.25 6.25 5.25Q19 16.25 19 10q0-4.75-5.5-4.75q-2.318 0-4.046 1.458");
}

</style>
