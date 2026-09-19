<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf8q-hhgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-videocam-off" /></template>
<style>
.nf8q-hhgu {
  fill: currentColor;
  d: path("M21 16.61V6.5l-4 4V6h-6.61zM3.41 1.86L2 3.27L4.73 6H3v12h13.73l3 3l1.41-1.41z");
}

</style>
