<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxvq_hrow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tilt-arrow-down-sharp" /></template>
<style>
.hxvq_hrow {
  fill: currentColor;
  d: path("M4 21V3h16v18zm7-8.825L9.4 10.6L8 12l4 4l4-4l-1.4-1.425l-1.6 1.6V8h-2z");
}

</style>
