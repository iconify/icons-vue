<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf-2kvb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-photo-camera-back" /></template>
<style>
.uf-2kvb5q {
  fill: currentColor;
  d: path("M16.83 5L15 3H9L7.17 5H2v16h20V5zM6 17l3-4l2.25 3l3-4L18 17z");
}

</style>
