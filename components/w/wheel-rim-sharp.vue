<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="b7uj2sbpm"/><path class="n6936rbpn"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wheel-rim-sharp" /></template>
<style>
.b7uj2sbpm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.1a6.9 6.9 0 1 0 0 13.8a6.9 6.9 0 0 0 0-13.8Z");
}

.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n6936rbpn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.43 9.12l-.57-1.15l-.27-.53l.48.35l2.6 1.89l.49.35l-.6-.09l-1.26-.2l-.6-.09zm1.75 3.35l.91-.9l.43-.42l-.18.57l-1 3.05l-.18.57l-.1-.59l-.21-1.26l-.09-.59zm-2.65 2.7l1.14.59l.54.28H9.79l.54-.28l1.14-.59l.53-.27zm-3.38-1.68l-.21 1.26l-.1.59l-.18-.57l-1-3.05l-.18-.57l.43.42l.91.9l.42.43zm.55-3.75l-1.26.2l-.6.09l.49-.35l2.6-1.89l.48-.35l-.27.53l-.57 1.15l-.27.53z");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
