<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7aztsb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:movie-off-outline" /></template>
<style>
.a7aztsb8w {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4l6 6H4v8h14l2 2zm17.775-1.1L20 17.125V10h-7.15l-6-6H8.5l1.675 3.325l.675.675h2.65l-2-4H14l2 4h3l-2-4h3q.825 0 1.413.588T22 6v12q0 .25-.05.475t-.175.425m-2 3.725l-18.4-18.4L2.8 2.8l18.4 18.4zm-3.35-9.075");
}

</style>
