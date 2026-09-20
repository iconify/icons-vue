<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="polg1ibmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:slideshow-outline-rounded" /></template>
<style>
.polg1ibmx {
  fill: currentColor;
  d: path("M15.85 12.425q.225-.15.225-.425t-.225-.425L10.275 8q-.25-.175-.513-.025t-.262.45v7.15q0 .3.263.45t.512-.025zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14z");
}

</style>
