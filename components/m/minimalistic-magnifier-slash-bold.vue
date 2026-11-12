<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-5f2htjo"/><path clip-rule="evenodd" class="by5ahfv2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifier-slash-bold" /></template>
<style>
.by5ahfv2m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5 2C16.7467 2 21 6.25329 21 11.5C21 16.7467 16.7467 21 11.5 21C6.25329 21 2 16.7467 2 11.5C2 6.25329 6.25329 2 11.5 2ZM13.7979 9.20215C13.505 8.90926 13.0302 8.90926 12.7373 9.20215L9.20215 12.7373C8.90926 13.0302 8.90926 13.505 9.20215 13.7979C9.49504 14.0907 9.9698 14.0907 10.2627 13.7979L13.7979 10.2627C14.0907 9.9698 14.0907 9.49504 13.7979 9.20215Z");
}

.x-5f2htjo {
  fill: currentColor;
  d: path("M19.4697 19.4697C19.7626 19.1768 20.2374 19.1768 20.5303 19.4697L22.5303 21.4697C22.8231 21.7626 22.8231 22.2374 22.5303 22.5303C22.2374 22.8231 21.7626 22.8231 21.4697 22.5303L19.4697 20.5303C19.1768 20.2374 19.1768 19.7626 19.4697 19.4697Z");
}

</style>
