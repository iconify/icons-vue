<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b3syo7bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:toloshare" /></template>
<style>
.b3syo7bme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.703 43.5h26.594m-13.26 0V30.609m15.191-8.429c-.001-7.473-6.537-8.84-6.537-8.84s-.435-8.84-8.64-8.84s-8.742 8.84-8.742 8.84s-6.536 1.367-6.537 8.84c-.003 10.684 13.502 8.62 15.265 8.429c1.763.19 15.194 2.255 15.191-8.429");
}

</style>
