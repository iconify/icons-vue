<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i533tgbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-fork-left" /></template>
<style>
.i533tgbva {
  fill: currentColor;
  d: path("M9.41 15.59L8 17l-4-4l4-4l1.41 1.41L7.83 12c1.51-.33 3.73.08 5.17 1.36V6.83l-1.59 1.59L10 7l4-4l4 4l-1.41 1.41L15 6.83V21h-2v-4c-.73-2.58-3.07-3.47-5.17-3z");
}

</style>
