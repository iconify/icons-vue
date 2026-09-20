<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfs90xbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:window-rounded" /></template>
<style>
.hfs90xbln {
  fill: currentColor;
  d: path("M13 13h8v6q0 .825-.587 1.413T19 21h-6zm0-2V3h6q.825 0 1.413.588T21 5v6zm-2 0H3V5q0-.825.588-1.412T5 3h6zm0 2v8H5q-.825 0-1.412-.587T3 19v-6z");
}

</style>
