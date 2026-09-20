<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yfvhhp1da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-315-right-16-regular" /></template>
<style>
.yfvhhp1da {
  fill: currentColor;
  d: path("M14.501 6a.5.5 0 0 1 .5.5V9a.5.5 0 0 1-1 0V7.706l-7.148 7.147a.5.5 0 0 1-.707-.707L13.294 7h-1.293a.5.5 0 0 1 0-1zM1.146 5.146a.5.5 0 0 1 .563-.1l6.5 3a.501.501 0 0 1-.419.908l-1.947-.9l-1.788 1.789l.9 1.948a.5.5 0 1 1-.907.418l-3.002-6.5l-.027-.072a.5.5 0 0 1 .127-.49m2.463 3.729l1.266-1.267l-2.352-1.086zM9.502 1a.5.5 0 0 1 .5.5V4a.5.5 0 0 1-1 0V2.707L6.354 5.355a.5.5 0 0 1-.707-.707L8.295 2H7.002a.5.5 0 1 1 0-1z");
}

</style>
