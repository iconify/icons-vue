<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duqj0ebvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microphone-off-fill" /></template>
<style>
.duqj0ebvb {
  fill: currentColor;
  d: path("m3.707 1.293l19 19a.999.999 0 1 1-1.414 1.414l-4.387-4.386A8 8 0 0 1 13 18.939V21a1 1 0 0 1-2 0v-2.061A8.006 8.006 0 0 1 4 11v-1a1 1 0 0 1 2 0v1a6 6 0 0 0 9.477 4.892l-1.445-1.446A3.999 3.999 0 0 1 8 11V8.414L2.293 2.707a.999.999 0 1 1 1.414-1.414m6.551 3.723l-1.44-1.441A4 4 0 0 1 16 6v4.757Z");
}

</style>
