<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf-gaf8dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:space-fill-round" /></template>
<style>
.sf-gaf8dt {
  fill: currentColor;
  d: path("M5 11a3 3 0 0 0 3 3h8c.796 0 1.559-.316 2.121-.879A3 3 0 0 0 19 11V9a1 1 0 0 1 2 0v2a5 5 0 0 1-5 5H8a5 5 0 0 1-5-5V9a1 1 0 0 1 2 0Z");
}

</style>
