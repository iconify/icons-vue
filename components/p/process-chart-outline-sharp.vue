<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxmm2orvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:process-chart-outline-sharp" /></template>
<style>
.uxmm2orvf {
  fill: currentColor;
  d: path("m3.3 18.45l-1.8-.9l6-12l1.8.9zm6.6 0l-1.8-.9l6-12l1.8.9zm6.6 0l-1.8-.9l6-12l1.8.9z");
}

</style>
