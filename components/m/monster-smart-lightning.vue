<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zltxzccqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:monster-smart-lightning" /></template>
<style>
.zltxzccqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 10.5C14.717 10.5 23 18.783 23 29v8.5H4.5zm39 0C33.283 10.5 25 18.783 25 29v8.5h18.5z");
}

</style>
