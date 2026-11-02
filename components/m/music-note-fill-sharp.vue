<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqt9k4bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-note-fill-sharp" /></template>
<style>
.iqt9k4bgx {
  fill: currentColor;
  d: path("M11 4a1 1 0 0 1 1.447-.894l6 3a1 1 0 1 1-.894 1.788L13 5.618V17a4.001 4.001 0 1 1-2-3.465Z");
}

</style>
