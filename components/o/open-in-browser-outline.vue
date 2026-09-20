<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1p_4g8hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:open-in-browser-outline" /></template>
<style>
.b1p_4g8hk {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21h-4v-2h4V7H5v12h4v2zm6 0v-6.15l-1.6 1.6L8 15l4-4l4 4l-1.4 1.45l-1.6-1.6V21z");
}

</style>
