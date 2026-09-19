<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="aqszcbwbb"/><circle class="w3n24fbgj"/><path class="rw4d7hzjy"/><path class="w9pxaxgbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-taxi-alert" /></template>
<style>
.aqszcbwbb {
  cx: 6.5px;
  cy: 15.5px;
  r: 1.5px;
  fill: currentColor;
}

.rw4d7hzjy {
  fill: currentColor;
  d: path("M18 13v5H4v-5zc-1.91 0-3.63-.76-4.89-2h-8.3l1.04-3h5.44C11.1 7.37 11 6.7 11 6s.1-1.37.29-2H8v2H5.5c-.66 0-1.21.42-1.42 1.01L2 13v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-8l-.09-.27c-.61.17-1.25.27-1.91.27");
}

.w3n24fbgj {
  cx: 15.5px;
  cy: 15.5px;
  r: 1.5px;
  fill: currentColor;
}

.w9pxaxgbc {
  fill: currentColor;
  d: path("M18 1c-2.76 0-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5s-2.24-5-5-5m.5 8h-1V8h1zm0-2h-1V3h1z");
}

</style>
