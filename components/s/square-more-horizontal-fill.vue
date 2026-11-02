<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5bxgeb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-more-horizontal-fill" /></template>
<style>
.t5bxgeb6u {
  fill: currentColor;
  d: path("M5 2h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m3 9a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm4 0a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm4.01 0H16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
