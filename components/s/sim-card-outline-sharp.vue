<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0buo_vlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sim-card-outline-sharp" /></template>
<style>
.t0buo_vlm {
  fill: currentColor;
  d: path("M7 19h2v-2H7zm0-4h2v-4H7zm4 4h2v-4h-2zm0-6h2v-2h-2zm4 6h2v-2h-2zm0-4h2v-4h-2zM4 22V8l6-6h10v20zm2-2h12V4h-7.15L6 8.85zm0 0h12z");
}

</style>
