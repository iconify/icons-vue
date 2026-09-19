<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxqpkenrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-ssid-chart" /></template>
<style>
.dxqpkenrq {
  fill: currentColor;
  d: path("M21 5.47L12 12L7.62 7.62L3 11V8.52L7.83 5l4.38 4.38L21 3zM21 15h-4.7l-4.17 3.34L6 12.41l-3 2.13V17l2.8-2l6.2 6l5-4h4z");
}

</style>
