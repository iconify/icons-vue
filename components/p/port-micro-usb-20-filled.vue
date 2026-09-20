<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y_puwdbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:port-micro-usb-20-filled" /></template>
<style>
.y_puwdbzt {
  fill: currentColor;
  d: path("M6.433 8.3a1.5 1.5 0 0 1 .9-.3h5.334c.324 0 .64.105.9.3l1.333 1A1.5 1.5 0 0 1 14 12H6a1.5 1.5 0 0 1-.9-2.7z");
}

</style>
