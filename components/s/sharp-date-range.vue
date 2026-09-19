<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml88e78xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-date-range" /></template>
<style>
.ml88e78xn {
  fill: currentColor;
  d: path("M9 11H7v2h2zm4 0h-2v2h2zm4 0h-2v2h2zm4-7h-3V2h-2v2H8V2H6v2H3v18h18zm-2 16H5V9h14z");
}

</style>
