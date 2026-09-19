<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8dazq48f"/><path class="uchiku29y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-medication-liquid" /></template>
<style>
.uchiku29y {
  fill: currentColor;
  d: path("M14 6H4c-1.1 0-2 .9-2 2v11c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2m0 13H4V8h10zm6-13c-1.68 0-3 1.76-3 4c0 1.77.83 3.22 2 3.76V20c0 .55.45 1 1 1s1-.45 1-1v-6.24c1.17-.54 2-1.99 2-3.76c0-2.24-1.32-4-3-4m0 6c-.41 0-1-.78-1-2s.59-2 1-2s1 .78 1 2s-.59 2-1 2");
}

.z8dazq48f {
  fill: currentColor;
  d: path("M3 3h12v2H3zm4.5 14.5h3V15H13v-3h-2.5V9.5h-3V12H5v3h2.5z");
}

</style>
