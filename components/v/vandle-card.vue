<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sk1301yss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vandle-card" /></template>
<style>
.sk1301yss {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 36.616c3.424 0 6.86.701 10.939.701c4.728 0 8.561-5.962 8.561-13.317s-3.833-13.317-8.561-13.317c-4.08 0-7.515.701-10.939.701s-6.86-.701-10.939-.701C8.333 10.683 4.5 16.645 4.5 24s3.833 13.317 8.561 13.317c4.08 0 7.515-.701 10.939-.701M13.5 21.25h21");
}

</style>
