<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9sgpuv3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:photo-album" /></template>
<style>
.w9sgpuv3v {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4v16q0 .825-.587 1.413T18 22zm1-4h10l-3.375-4.5L11 17l-1.625-2.175zm4-7l2.5-1.5L16 11V4h-5z");
}

</style>
