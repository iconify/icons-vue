<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha2c_zbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:reset-tv-outline" /></template>
<style>
.ha2c_zbyc {
  fill: currentColor;
  d: path("M8 21v-2H4q-.825 0-1.412-.587T2 17V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v3h-2V5H4v12h16v-5h-7.2l1.85 1.85l-1.4 1.4L9 11l4.25-4.25l1.4 1.4L12.8 10H20q.825 0 1.413.588T22 12v5q0 .825-.587 1.413T20 19h-4v2zm5-10");
}

</style>
