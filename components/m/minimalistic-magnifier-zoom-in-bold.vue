<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-5f2htjo"/><path clip-rule="evenodd" class="qsu2hybgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifier-zoom-in-bold" /></template>
<style>
.qsu2hybgb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5 2C16.7467 2 21 6.25329 21 11.5C21 16.7467 16.7467 21 11.5 21C6.25329 21 2 16.7467 2 11.5C2 6.25329 6.25329 2 11.5 2ZM11.5 8.25C11.0858 8.25 10.75 8.58579 10.75 9V10.75H9C8.58579 10.75 8.25 11.0858 8.25 11.5C8.25 11.9142 8.58579 12.25 9 12.25H10.75V14C10.75 14.4142 11.0858 14.75 11.5 14.75C11.9142 14.75 12.25 14.4142 12.25 14V12.25H14C14.4142 12.25 14.75 11.9142 14.75 11.5C14.75 11.0858 14.4142 10.75 14 10.75H12.25V9C12.25 8.58579 11.9142 8.25 11.5 8.25Z");
}

.x-5f2htjo {
  fill: currentColor;
  d: path("M19.4697 19.4697C19.7626 19.1768 20.2374 19.1768 20.5303 19.4697L22.5303 21.4697C22.8231 21.7626 22.8231 22.2374 22.5303 22.5303C22.2374 22.8231 21.7626 22.8231 21.4697 22.5303L19.4697 20.5303C19.1768 20.2374 19.1768 19.7626 19.4697 19.4697Z");
}

</style>
