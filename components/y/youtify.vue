<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jo3zqub6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:youtify" /></template>
<style>
.jo3zqub6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 24.306h-7.843l-4.355-7.774l-6.398 21.485l-6.979-28.034l-5.582 14.323H4.5");
}

</style>
