<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0mhzyszz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:select-window-2-outline-sharp" /></template>
<style>
.j0mhzyszz {
  fill: currentColor;
  d: path("M4 20h12.23v-9.384H4zm13.23-5.616v-1H20V4H7.77v5.616h-1V3H21v11.385zM3 21V9.616h14.23V21zm7.116-5.692");
}

</style>
