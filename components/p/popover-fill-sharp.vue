<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7isffc7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:popover-fill-sharp" /></template>
<style>
.l7isffc7n {
  fill: currentColor;
  d: path("M3 6h5.5l2.7-3.6a1 1 0 0 1 1.6 0L15.5 6H21a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1m14 5H7a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2M7 15a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2Z");
}

</style>
