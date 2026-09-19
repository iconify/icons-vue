<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l832-6puf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-7k" /></template>
<style>
.l832-6puf {
  fill: currentColor;
  d: path("M21 3H3v18h18zM9.5 15H7.75l1.38-4.5H6.5V9h4.86zm8.5 0h-1.75l-1.75-2.25V15H13V9h1.5v2.25L16.25 9H18l-2.25 3z");
}

</style>
