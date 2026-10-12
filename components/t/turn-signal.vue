<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnjtcbbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:turn-signal" /></template>
<style>
.nnjtcbbtd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.3 11.49l4.65-4.23q.55-.51.55.24V9q0 .75.75.75H10q.75 0 .75.75v3q0 .75-.75.75h-.75q-.75 0-.75.75v1.5q0 .75-.55.24L3.3 12.51q-.55-.51 0-1.02m17.4 0l-4.65-4.23q-.55-.51-.55.24V9q0 .75-.75.75H14q-.75 0-.75.75v3q0 .75.75.75h.75q.75 0 .75.75v1.5q0 .75.55.24l4.65-4.23q.55-.51 0-1.02");
}

</style>
