<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qjd_9mrbq"/><path class="x4nywcc9w"/><path class="mgkbck2ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oeffidirections" /></template>
<style>
.mgkbck2ke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.19 16.56l-4.73 2.74l-4.73 2.73V11.1z");
}

.qjd_9mrbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.5 21.5 0 1 0 45.5 24A21.51 21.51 0 0 0 24 2.5");
}

.x4nywcc9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.81 36.9V22.56a6 6 0 0 1 6-6h4.92");
}

</style>
