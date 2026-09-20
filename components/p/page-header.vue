<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixw60nbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:page-header" /></template>
<style>
.ixw60nbui {
  fill: currentColor;
  d: path("M3 5V3h18v2zm16 2q.825 0 1.413.588T21 9v10q0 .825-.587 1.413T19 21H5q-.825 0-1.412-.587T3 19V9q0-.825.588-1.412T5 7z");
}

</style>
