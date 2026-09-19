<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z9_3qbblu"/><path class="nj71yb4fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:webui-x" /></template>
<style>
.nj71yb4fg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.912 22.238c10.465-4.622 11.479 3.82 21.565-.377M25.637 6.47l12.03 3.223m-6.235-1.446l-3.937 14.695");
}

.z9_3qbblu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.327 16.738l2.05 13.488c.04.271.123 1.629.123 1.902v3.454c0 2.817-3.184 5.949-6 5.949h-25c-2.816 0-6-3.132-6-5.949V32.13c0-.275.083-1.632.123-1.903l2.228-14.662c.588-3.874 1.885-4.98 4.98-4.98h7.191M5.851 31.116h36.298");
}

</style>
