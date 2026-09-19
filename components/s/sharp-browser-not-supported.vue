<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emlgycbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-browser-not-supported" /></template>
<style>
.emlgycbqx {
  fill: currentColor;
  d: path("M19 6v10.5l2 2V4H6.5l2 2zM3.22 3.32L1.95 4.59L3 5.64V20h14.36l2.06 2.06l1.27-1.27zM15 18H5V7.64L15.36 18z");
}

</style>
