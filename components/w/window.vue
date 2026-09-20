<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="envz6nbxv"/><path class="sxvkzgbfy"/><path class="gkwu3tbqk"/><path class="giy_w11px"/><path class="arzuy7b3l"/><path class="ibfp8qbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:window" /></template>
<style>
.arzuy7b3l {
  fill: var(--svg-color--bf6952, #bf6952);
  d: path("M17 2h2v32h-2z");
}

.envz6nbxv {
  fill: var(--svg-color--d79e84, #d79e84);
  d: path("M35 36H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h34c.55 0 1 .45 1 1v34c0 .55-.45 1-1 1");
}

.giy_w11px {
  fill: var(--svg-color--fff, #fff);
  d: path("M2 34V2h32z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gkwu3tbqk {
  fill: var(--svg-color--8ccaf7, #8ccaf7);
  d: path("M2 2h32v32H2z");
}

.ibfp8qbnw {
  fill: var(--svg-color--bf6952, #bf6952);
  d: path("M2 19v-2h32v2z");
}

.sxvkzgbfy {
  fill: var(--svg-color--bf6952, #bf6952);
  d: path("M1 36h34c.55 0 1-.45 1-1V1a1 1 0 0 0-.294-.706L.294 35.706A1 1 0 0 0 1 36");
}

</style>
