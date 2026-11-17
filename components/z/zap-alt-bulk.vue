<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehz-qpbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-alt-bulk" /></template>
<style>
.ehz-qpbrr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.707 15.707L8.414 21a1.292 1.292 0 0 1-2.173-1.193L7.753 13H7a1.65 1.65 0 0 1-1.508-2.32l3.33-7.492A2 2 0 0 1 10.65 2H16a1.582 1.582 0 0 1 1.372 2.364L14.723 9H17a1.416 1.416 0 0 1 1 2.414Z");
}

</style>
