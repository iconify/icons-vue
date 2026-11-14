<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go7o74b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stationery-store" /></template>
<style>
.go7o74b9t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.311 6.205l19.439.274v.022q-.002 2.997-3 2.997q-1.499 0-2.249-.749q-.75.751-2.251.751T12 8.75q-.75.75-2.25.75t-2.251-.751q-.75.75-2.249.75q-2.999 0-3-2.999q0-.154.061-.295M5.75 12.25q0-2.5 2.5-2.5h7.5q2.5 0 2.5 2.5v7.5q0 1.036-.732 1.768t-1.768.732h-7.5q-1.036 0-1.768-.732T5.75 19.75z");
}

</style>
