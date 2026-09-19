<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp097gb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-filter-frames" /></template>
<style>
.kp097gb6u {
  fill: currentColor;
  d: path("M20 4h-4l-4-4l-4 4H4c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 16H4V6h4.52l3.52-3.5L15.52 6H20zM6 18h12V8H6zm2-8h8v6H8z");
}

</style>
