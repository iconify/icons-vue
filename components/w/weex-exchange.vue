<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vh7glnnku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:weex-exchange" /></template>
<style>
.vh7glnnku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.5 14.25H11l-6.5 6.5l13 13l13-13l-6.5-6.5l-6.5 6.5l13 13l13-13l-6.5-6.5h-6.5");
}

</style>
