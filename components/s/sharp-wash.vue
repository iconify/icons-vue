<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib1ys1-iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-wash" /></template>
<style>
.ib1ys1-iy {
  fill: currentColor;
  d: path("M9.12 5L1 12.68V23h18v-2.5h-7v-1h9V17h-9v-1h10v-2.5H12v-1h8V10H8.86l1.88-3.3zm4.38 4c.83 0 1.5-.67 1.5-1.5c0-.84-1.5-2.5-1.5-2.5S12 6.66 12 7.5c0 .83.67 1.5 1.5 1.5m5-8S16 3.83 16 5.5a2.5 2.5 0 0 0 5 0C21 3.83 18.5 1 18.5 1");
}

</style>
