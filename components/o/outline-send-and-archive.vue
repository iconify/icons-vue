<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y19g5joxc"/><path class="n269rbc3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-send-and-archive" /></template>
<style>
.n269rbc3i {
  fill: currentColor;
  d: path("M17 12c-2.76 0-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5s-2.24-5-5-5m0 8l-3-3l.71-.71l1.79 1.79V14h1v4.09l1.79-1.79l.71.7z");
}

.y19g5joxc {
  fill: currentColor;
  d: path("m11 12l-6-1.5V7.01l8.87 3.73c.94-.47 2-.75 3.13-.75c.1 0 .19.01.28.01L3 4v16l7-2.95V17c0-.8.14-1.56.39-2.28L5 16.99V13.5z");
}

</style>
