<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds--j-b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-swipe-up-alt" /></template>
<style>
.ds--j-b0x {
  fill: currentColor;
  d: path("m13 5.83l1.59 1.59L16 6l-4-4l-4 4l1.41 1.41L11 5.83v4.27a5 5 0 1 0 2 0z");
}

</style>
