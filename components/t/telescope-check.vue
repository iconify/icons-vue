<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spx7bg5ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:telescope-check" /></template>
<style>
.spx7bg5ts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.232 8.164l10.423-4.86a1.75 1.75 0 0 1 2.325.847l.634 1.359a1.75 1.75 0 0 1-.846 2.326l-10.423 4.86a1.75 1.75 0 0 1-2.325-.847l-.634-1.359a1.75 1.75 0 0 1 .846-2.326M10.5 10.75L6.5 21m4-10.25l1.658 6.181m.881 3.284l.211.785m1.5-3l2 2L21 15.75");
}

</style>
