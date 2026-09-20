<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wio8cjbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tooltip-outline-sharp" /></template>
<style>
.wio8cjbji {
  fill: currentColor;
  d: path("m12 21l-2.29-3.5H3V3h18v14.5h-6.71zm0-1.811l1.754-2.689H20V4H4v12.5h6.246zm0-8.939");
}

</style>
