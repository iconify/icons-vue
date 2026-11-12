<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdjsjkv6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:popover-fill-round" /></template>
<style>
.tdjsjkv6x {
  fill: currentColor;
  d: path("M7 6h1.5l2.7-3.6a1 1 0 0 1 1.6 0L15.5 6H17a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5v-6a5 5 0 0 1 5-5m10 5H7a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2M7 15a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2Z");
}

</style>
