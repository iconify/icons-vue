<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuhog5tho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-network-ping" /></template>
<style>
.yuhog5tho {
  fill: currentColor;
  d: path("M2.71 6.79a.996.996 0 0 0 0 1.41L10.5 16H5c-.55 0-1 .45-1 1s.45 1 1 1h14c.55 0 1-.45 1-1s-.45-1-1-1h-5.5l5.15-5.15A2.5 2.5 0 1 0 19.5 6A2.5 2.5 0 0 0 17 8.5c0 .35.07.67.2.97l-5.2 5.2l-7.88-7.88a.996.996 0 0 0-1.41 0");
}

</style>
