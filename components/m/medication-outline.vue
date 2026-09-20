<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf4wryaqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:medication-outline" /></template>
<style>
.kf4wryaqi {
  fill: currentColor;
  d: path("M10.5 17.5h3V15H16v-3h-2.5V9.5h-3V12H8v3h2.5zM7 21q-.825 0-1.412-.587T5 19V8q0-.825.588-1.412T7 6h10q.825 0 1.413.588T19 8v11q0 .825-.587 1.413T17 21zm0-2h10V8H7zM6 5V3h12v2zm1 3v11z");
}

</style>
