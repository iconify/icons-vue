<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs29x6brz"/><circle class="sepm5fbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-location-on" /></template>
<style>
.sepm5fbik {
  cx: 12px;
  cy: 9px;
  r: 2.5px;
  fill: currentColor;
}

.zs29x6brz {
  fill: currentColor;
  d: path("M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7M7 9c0-2.76 2.24-5 5-5s5 2.24 5 5c0 2.88-2.88 7.19-5 9.88C9.92 16.21 7 11.85 7 9");
}

</style>
