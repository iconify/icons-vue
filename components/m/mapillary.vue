<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sp7h_hbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mapillary" /></template>
<style>
.sp7h_hbpb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.003 18.58l-6.17-12.52A1.003 1.003 0 0 0 23 6.135l-4.296 10.88a2 2 0 0 1-1.195 1.153l-11.025 3.91a1.003 1.003 0 0 0-.14 1.828l12.294 6.609m15.008-6.571l8.43 17.105a1.003 1.003 0 0 1-1.374 1.327l-16.796-9.03");
}

</style>
