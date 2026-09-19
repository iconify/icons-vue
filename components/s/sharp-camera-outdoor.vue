<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoml00bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-camera-outdoor" /></template>
<style>
.xoml00bat {
  fill: currentColor;
  d: path("M18 14v-2h-6v6h6v-2l2 1.06v-4.12zM12 3L4 9v12h16v-2H6v-9l6-4.5l6 4.5v1h2V9z");
}

</style>
