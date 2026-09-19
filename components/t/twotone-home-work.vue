<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms873rdco"/><path class="l10j5zb2d"/><path class="gd9flbcds"/><path class="s0a2z0fjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-home-work" /></template>
<style>
.gd9flbcds {
  fill: currentColor;
  d: path("M3 12v7h2v-5h6v5h2v-7L8 8.5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.l10j5zb2d {
  fill: currentColor;
  d: path("M10 3v1.97l.96.69L12 6.4V5h9v14h-4v2h6V3z");
}

.ms873rdco {
  fill: currentColor;
  d: path("M17 11h2v2h-2v2h2v2h-2v2h4V5h-9v1.4l5 3.57zm0-4h2v2h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.s0a2z0fjn {
  fill: currentColor;
  d: path("M17 7h2v2h-2zm0 4h2v2h-2zm0 4h2v2h-2zM1 11v10h6v-5h2v5h6V11L8 6zm12 8h-2v-5H5v5H3v-7l5-3.5l5 3.5z");
}

</style>
