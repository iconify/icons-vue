<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qqjv61b4r"/><path class="jtb_usbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:questmobile" /></template>
<style>
.jtb_usbay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.536 15.895c-5.95.628-15.44 15.854-13.035 23.305m8.288.111c5.948-3.93 8.33-9.48 9.497-16.066m-7.375 8.195l4.597 7.773");
}

.qqjv61b4r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.033 8.667L4.5 39.333l39-.067Z");
}

</style>
