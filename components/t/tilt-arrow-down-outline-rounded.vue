<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3hf4rbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tilt-arrow-down-outline-rounded" /></template>
<style>
.z3hf4rbdl {
  fill: currentColor;
  d: path("M6 21q-.825 0-1.412-.587T4 19V5q0-.825.588-1.412T6 3h12q.825 0 1.413.588T20 5v14q0 .825-.587 1.413T18 21zm0-2h12V5H6zm5-6.825l-.9-.9Q9.825 11 9.413 11t-.713.3q-.275.275-.275.7t.275.7l2.6 2.6q.3.3.7.3t.7-.3l2.6-2.6q.275-.275.275-.687T15.3 11.3q-.3-.3-.712-.3t-.713.3l-.875.875V9q0-.425-.288-.712T12 8t-.712.288T11 9zM18 19H6z");
}

</style>
