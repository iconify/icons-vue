<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp5tthb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:save-as" /></template>
<style>
.cp5tthb0i {
  fill: currentColor;
  d: path("M13 23v-3.075l5.525-5.5q.225-.225.5-.325t.55-.1q.3 0 .575.113t.5.337l.925.925q.2.225.313.5t.112.55t-.1.563t-.325.512l-5.5 5.5zM6 10h9V6H6zm13.575 7.4l.925-.975l-.925-.925l-.95.95zM11 21H5q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h12l4 4v5.3q-.475-.2-.987-.262T19 12.05t-.975.313t-.875.612L15 15.125V15q0-1.25-.875-2.125T12 12t-2.125.875T9 15t.875 2.125T12 18h.1L11 19.1z");
}

</style>
