<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0a2z0fjn"/><path class="hmo41kyjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-maps-home-work" /></template>
<style>
.hmo41kyjx {
  fill: currentColor;
  d: path("M10 3v1.97l2 1.43V5h9v14h-4v2h6V3z");
}

.s0a2z0fjn {
  fill: currentColor;
  d: path("M17 7h2v2h-2zm0 4h2v2h-2zm0 4h2v2h-2zM1 11v10h6v-5h2v5h6V11L8 6zm12 8h-2v-5H5v5H3v-7l5-3.5l5 3.5z");
}

</style>
