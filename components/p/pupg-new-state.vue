<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="estu-r_5b"/><path class="v_l2rtb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pupg-new-state" /></template>
<style>
.estu-r_5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.77 37.233C16.097 21.4 20.175 10.644 22.784 4.5c2.393 8.088 7.876 26.022 11.246 39");
}

.v_l2rtb5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.658 22.265c7.94-5.142 16.317-9.102 26.684-11.07c-5.053 3.992-6.134 4.993-8.264 7.95");
}

</style>
