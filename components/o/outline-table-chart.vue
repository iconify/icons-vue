<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh1_x1bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-table-chart" /></template>
<style>
.qh1_x1bmc {
  fill: currentColor;
  d: path("M20 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h15c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 2v3H5V5zm-5 14h-5v-9h5zM5 10h3v9H5zm12 9v-9h3v9z");
}

</style>
