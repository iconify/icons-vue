<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai8znbbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-stream" /></template>
<style>
.ai8znbbzz {
  fill: currentColor;
  d: path("M3 19v-6h18v6zm0-8V5h18v6z");
}

</style>
