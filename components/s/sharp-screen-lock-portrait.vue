<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyv0clbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-screen-lock-portrait" /></template>
<style>
.xyv0clbhd {
  fill: currentColor;
  d: path("M9 16h6v-5h-1v-.9c0-1-.69-1.92-1.68-2.08C11.07 7.83 10 8.79 10 10v1H9zm1.8-6c0-.66.54-1.2 1.2-1.2s1.2.54 1.2 1.2v1h-2.4zM19 1H5v22h14zm-2 18H7V5h10z");
}

</style>
