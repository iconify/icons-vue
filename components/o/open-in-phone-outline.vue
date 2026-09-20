<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwj9exb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:open-in-phone-outline" /></template>
<style>
.bwj9exb9t {
  fill: currentColor;
  d: path("M7 23q-.825 0-1.412-.587T5 21v-6h2v3h10V6H7v3H5V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v18q0 .825-.587 1.413T17 23zm0-3v1h10v-1zm3-4l-1.4-1.4l1.55-1.6H2v-2h8.15L8.6 9.4L10 8l4 4zM7 4h10V3H7zm0 0V3zm0 16v1z");
}

</style>
