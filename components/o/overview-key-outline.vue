<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl55uxb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:overview-key-outline" /></template>
<style>
.gl55uxb8x {
  fill: currentColor;
  d: path("M3 19q-.825 0-1.412-.587T1 17V7q0-.825.588-1.412T3 5h10q.825 0 1.413.588T15 7v10q0 .825-.587 1.413T13 19zm0-2h10V7H3zm14 2V5h2v14zm4 0V5h2v14zM3 17V7z");
}

</style>
