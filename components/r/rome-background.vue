<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="y_i_l7tjf"/><path class="pjfg_hw5k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rome-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pjfg_hw5k {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.175 5.306c1.193.454 1.373 1.244 1.373 6.74c0 5.498-.113 5.859-1.44 6.556a.3.3 0 0 0-.108.123c.072.17 1.383.212 4.372.212c4.155 0 4.624-.03 3.963-.392a2.5 2.5 0 0 1-1.006-.976c-.377-.877-.31-10.286.031-11.23c.315-.76.268-.79 1.559-.672c2.802.336 4.062 1.884 4.062 5.105c0 2.245-.568 3.52-1.982 4.614c-.692.516-.98 1.063-1.136 2.158l-.211 1.424H20V17.24c0-1.672-.031-1.703-.506-1.063c-.408.578-.753.67-2.513.67c-2.013 0-2.674-.397-1.26-.732c1.136-.274 2.736-1.667 3.21-2.823c.661-1.487.568-4.005-.221-5.224c-1.637-2.58-3.071-3.065-9.833-3.034c-3.339 0-5.145.092-4.702.273m4.795.79c.093.273.191 2.978.191 6.039c0 4.438-.098 5.62-.444 5.894c-.877.696-1.3-.64-1.3-6.039c0-4.862.387-6.38 1.084-6.38c.154 0 .376.212.464.486z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y_i_l7tjf {
  fill: var(--svg-color--be1f3d, #be1f3d);
  d: path("M24 0H0v24h24z");
}

</style>
