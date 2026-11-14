<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u56g3md9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:repost-check" /></template>
<style>
.u56g3md9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7a7 7 0 0 1 13 3.5m-2-2l2 2l2-2m-7.993 8.9q-.186.026-.372.043q-.187.017-.374.024t-.374.004t-.374-.016t-.372-.036q-.186-.023-.37-.056q-.185-.032-.367-.075t-.362-.095t-.356-.114t-.35-.133q-.173-.072-.342-.152q-.169-.081-.334-.17q-.164-.089-.324-.187q-.159-.098-.313-.204q-.155-.107-.303-.221q-.148-.115-.29-.237q-.141-.122-.277-.252q-.135-.129-.263-.266q-.127-.137-.248-.28q-.12-.143-.233-.293q-.113-.149-.217-.305q-.105-.155-.201-.316q-.096-.16-.183-.326t-.166-.336t-.147-.344t-.129-.351q-.06-.177-.11-.358q-.05-.18-.091-.363t-.071-.367t-.051-.371t-.032-.373T4 10.5m-2 2l2-2l2 2m8.75 5.5l2 2L21 15.75");
}

</style>
