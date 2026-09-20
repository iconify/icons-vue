<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6sdmzp2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:right-panel-close-rounded" /></template>
<style>
.p6sdmzp2w {
  fill: currentColor;
  d: path("M7.5 14.8q0 .35.3.475t.55-.125l2.45-2.45q.3-.3.3-.7t-.3-.7L8.35 8.85q-.25-.25-.55-.125t-.3.475zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm9-2V5H5v14z");
}

</style>
