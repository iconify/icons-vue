<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k45938crj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:port-usb-c-20-regular" /></template>
<style>
.k45938crj {
  fill: currentColor;
  d: path("M4.5 10a2 2 0 0 1 2-2h7a2 2 0 1 1 0 4h-7a2 2 0 0 1-2-2m2-1a1 1 0 0 0 0 2h7a1 1 0 1 0 0-2z");
}

</style>
