<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdu0l2a4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:reorder" /></template>
<style>
.gdu0l2a4x {
  fill: currentColor;
  d: path("M3 15h18v-2H3zm0 4h18v-2H3zm0-8h18V9H3zm0-6v2h18V5z");
}

</style>
