<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3c1p2a-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:outgoing-mail-outline" /></template>
<style>
.m3c1p2a-d {
  fill: currentColor;
  d: path("m18 20l-1.4-1.4l1.575-1.6H14v-2h4.175L16.6 13.4L18 12l4 4zM4 17q-.825 0-1.412-.587T2 15V5q0-.825.588-1.412T4 3h13q.825 0 1.413.588T19 5v5.1q-.25-.05-.5-.075T18 10t-.5.013t-.5.062V6.4L10.4 11L4 6.425V15h8.075q-.05.25-.062.5T12 16t.025.5t.075.5zM5.45 5l4.95 3.55L15.5 5zM4 15V5z");
}

</style>
