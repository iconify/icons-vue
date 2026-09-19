<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9k252k4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-fork-right" /></template>
<style>
.n9k252k4f {
  fill: currentColor;
  d: path("M14.59 15.59L16 17l4-4l-4-4l-1.41 1.41L16.17 12c-1.51-.33-3.73.08-5.17 1.36V6.83l1.59 1.59L14 7l-4-4l-4 4l1.41 1.41L9 6.83V21h2v-4c.73-2.58 3.07-3.47 5.17-3z");
}

</style>
