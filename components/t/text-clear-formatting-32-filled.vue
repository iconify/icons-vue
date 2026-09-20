<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="of2rttg_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-clear-formatting-32-filled" /></template>
<style>
.of2rttg_q {
  fill: currentColor;
  d: path("m22.5 27.915l-.085.085H27a1 1 0 1 1 0 2h-8q-.042-.001-.083-.005a3.4 3.4 0 0 1-2.334-.998l-2.577-2.577a3.42 3.42 0 0 1-.001-4.837l1.08-1.082zm-.917-13.91a3.42 3.42 0 0 1 4.837 0l2.577 2.578a3.42 3.42 0 0 1 0 4.836L23.914 26.5L16.5 19.087zM8.5 2a1 1 0 0 1 .93.635l5.5 14a1 1 0 0 1-1.86.73L11.746 14H5.253L3.93 17.365a1 1 0 0 1-1.862-.73l5.5-14C7.748 2.265 8.07 2 8.5 2M18 2a1 1 0 0 1 1 1v5.095A4.66 4.66 0 0 1 22 7c2.869 0 5 2.576 5 5.5l-.001.023a4.9 4.9 0 0 0-2.101-.938C24.542 10.033 23.307 9 22 9c-1.55 0-3 1.453-3 3.5c0 .6.125 1.148.34 1.624L17 16.464V3a1 1 0 0 1 1-1M6.038 12h4.924L8.5 5.733z");
}

</style>
