<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dr2o35bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-humidity-16-filled" /></template>
<style>
.dr2o35bsw {
  fill: currentColor;
  d: path("M9.75 14a.5.5 0 0 1 0 1h-3.5a.5.5 0 0 1 0-1zm2-2a.5.5 0 0 1 0 1h-7.5a.5.5 0 0 1 0-1zm.75-2a.5.5 0 0 1 0 1h-9a.5.5 0 0 1 0-1zm0-2a.5.5 0 0 1 0 1h-9a.5.5 0 0 1 0-1zM7.647 1.147a.5.5 0 0 1 .707 0c.262.261 1.41 1.45 2.495 3.002c.59.845 1.184 1.83 1.598 2.851H3.555c.414-1.02 1.008-2.006 1.598-2.85a24 24 0 0 1 2.494-3.003");
}

</style>
