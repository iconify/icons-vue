<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol1d5gzqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:play-off" /></template>
<style>
.ol1d5gzqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.948 14.948L9.2585 19.5544C8.9024 19.8427 8.4582 20 8 20C6.8954 20 6 19.1046 6 18L6 6M13.6917 8.0348L17.6292 11.2228C17.8638 11.4127 18 11.6983 18 12C18 12.101 17.9847 12.2014 17.9546 12.2978M2 2L22 22");
}

</style>
