<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tiet3mbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:numbers-sharp" /></template>
<style>
.tiet3mbrt {
  fill: currentColor;
  d: path("m6 20l1-4H3l.5-2h4l1-4h-4L5 8h4l1-4h2l-1 4h4l1-4h2l-1 4h4l-.5 2h-4l-1 4h4l-.5 2h-4l-1 4h-2l1-4H9l-1 4zm3.5-6h4l1-4h-4z");
}

</style>
