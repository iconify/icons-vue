<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u-klbnwwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:steps-20-regular" /></template>
<style>
.u-klbnwwa {
  fill: currentColor;
  d: path("M11 3a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v4h-1V3h-3v3a1 1 0 0 1-1 1H8v3a1 1 0 0 1-1 1H4v3h4v1H4a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1h3V7a1 1 0 0 1 1-1h3zm3 5a1 1 0 0 0-1 1v3h-3a1 1 0 0 0-1 1v3a1 1 0 0 0 1 1h5.5a2.5 2.5 0 0 0 2.5-2.5V9a1 1 0 0 0-1-1zm0 1h3v5.5a1.5 1.5 0 0 1-1.5 1.5H10v-3h3a1 1 0 0 0 1-1z");
}

</style>
