<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="gmmxn3b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-moon-28-filled" /></template>
<style>
.gmmxn3b7x {
  fill: currentColor;
  d: path("M13.668 2.97a.75.75 0 0 1 .788-.93C20.627 2.536 25.48 7.7 25.48 14c0 6.628-5.373 12-12 12A12 12 0 0 1 3.1 20.028a.75.75 0 0 1 .47-1.106c1.599-.393 3.55-1.024 5.32-2.004c1.773-.983 3.31-2.287 4.169-4.003c1.713-3.427 1.26-7.345.608-9.945");
}

</style>
