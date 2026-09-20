<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-ev7zb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trending-flat-outline-sharp" /></template>
<style>
.l-ev7zb3x {
  fill: currentColor;
  d: path("m17.5 16.5l-1.425-1.4l2.1-2.1H3v-2h15.175L16.1 8.9l1.425-1.4L22 12z");
}

</style>
