<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq8hhbc8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-minus-fill-round" /></template>
<style>
.hq8hhbc8g {
  fill: currentColor;
  d: path("M22 8v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5M4 9v7a3.004 3.004 0 0 0 3 3h10a3 3 0 0 0 3-3V9Zm5 4h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
