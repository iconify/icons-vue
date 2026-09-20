<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg_bbbc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:microphone-chat-24-filled" /></template>
<style>
.eg_bbbc9i {
  fill: currentColor;
  d: path("M21.751 12.75a.75.75 0 0 1 .75.75a6 6 0 0 1-5.25 5.951v1.799a.75.75 0 0 1-1.5 0v-1.799a6 6 0 0 1-5.25-5.951a.75.75 0 0 1 1.5 0a4.5 4.5 0 0 0 9 0a.75.75 0 0 1 .75-.75M10.001 2c2.096 0 4.004.808 5.43 2.128a4.5 4.5 0 0 0-3.43 4.372v3.42a1.75 1.75 0 0 0-2.5 1.58c0 1.68.593 3.22 1.578 4.426a7.96 7.96 0 0 1-4.528-.712l-2.997.75a1.25 1.25 0 0 1-1.516-1.515l.75-2.998A8 8 0 0 1 2 10c0-4.418 3.583-8 8-8m6.5 3A3.5 3.5 0 0 1 20 8.5v5a3.5 3.5 0 0 1-7 0v-5A3.5 3.5 0 0 1 16.5 5");
}

</style>
