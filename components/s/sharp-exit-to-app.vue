<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmvky-vuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-exit-to-app" /></template>
<style>
.fmvky-vuf {
  fill: currentColor;
  d: path("M10.09 15.59L11.5 17l5-5l-5-5l-1.41 1.41L12.67 11H3v2h9.67zM21 3H3v6h2V5h14v14H5v-4H3v6h18z");
}

</style>
