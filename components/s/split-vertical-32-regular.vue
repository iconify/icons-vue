<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wlgtwzbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:split-vertical-32-regular" /></template>
<style>
.wlgtwzbdt {
  fill: currentColor;
  d: path("M15 29a1 1 0 1 0 2 0V3a1 1 0 1 0-2 0zm11.5-5h-8v2h8a3.5 3.5 0 0 0 3.5-3.5v-13A3.5 3.5 0 0 0 26.5 6h-8v2h8A1.5 1.5 0 0 1 28 9.5v13a1.5 1.5 0 0 1-1.5 1.5m-13-18h-8A3.5 3.5 0 0 0 2 9.5v13A3.5 3.5 0 0 0 5.5 26h8v-2h-8A1.5 1.5 0 0 1 4 22.5v-13A1.5 1.5 0 0 1 5.5 8h8z");
}

</style>
