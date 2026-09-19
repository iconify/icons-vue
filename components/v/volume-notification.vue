<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a15h8_bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:volume-notification" /></template>
<style>
.a15h8_bgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.243 31.431a5.742 5.742 0 1 0-11.484 0a5.742 5.742 0 0 0 11.484 0V10.828H42.5m-37 16.5h15.706M5.5 19.078h23.8M5.5 10.827h23.8");
}

</style>
