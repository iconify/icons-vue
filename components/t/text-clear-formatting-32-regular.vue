<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fb98lac-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-clear-formatting-32-regular" /></template>
<style>
.fb98lac-w {
  fill: currentColor;
  d: path("M21.582 14.004a3.42 3.42 0 0 1 4.836 0l2.578 2.578a3.42 3.42 0 0 1 0 4.836L22.414 28H27a1 1 0 1 1 0 2h-8l-.082-.004a3.4 3.4 0 0 1-2.336-1l-2.577-2.577a3.42 3.42 0 0 1-.001-4.837zm-6.164 8.992a1.42 1.42 0 0 0 0 2.008l2.578 2.578a1.42 1.42 0 0 0 2.008 0l1.082-1.082l-4.586-4.586zm9.586-7.578a1.42 1.42 0 0 0-2.008 0L17.914 20.5l4.586 4.586l5.082-5.082a1.42 1.42 0 0 0 0-2.008zM8.5 2a1 1 0 0 1 .93.635l5.5 14a1 1 0 0 1-1.86.73L11.746 14H5.253L3.93 17.365a1 1 0 0 1-1.862-.73l5.5-14C7.748 2.265 8.07 2 8.5 2M18 2a1 1 0 0 1 1 1v5.095A4.66 4.66 0 0 1 22 7c2.869 0 5 2.576 5 5.5l-.001.023a4.9 4.9 0 0 0-2.101-.938C24.542 10.033 23.307 9 22 9c-1.55 0-3 1.453-3 3.5c0 .6.125 1.148.34 1.624L17 16.464V3a1 1 0 0 1 1-1M6.038 12h4.924L8.5 5.733z");
}

</style>
