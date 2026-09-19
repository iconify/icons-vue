<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us55ghb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-door-sliding" /></template>
<style>
.us55ghb4b {
  fill: currentColor;
  d: path("M10 13H8v-2h2zm6-2h-2v2h2zm5 8v2H3v-2h1V5c0-1.1.9-2 2-2h12c1.1 0 2 .9 2 2v14zM11 5H6v14h5zm7 0h-5v14h5z");
}

</style>
