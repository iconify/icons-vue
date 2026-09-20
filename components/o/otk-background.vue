<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG9XmjqcWJ)" class="r4i437pya"/><path class="u8koxhvda"/></g><defs><linearGradient id="SVG9XmjqcWJ" x1="12.002" x2="12.002" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="cgj9ggbwn"/><stop offset="1" class="zdxws8cls"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:otk-background" /></template>
<style>
.cgj9ggbwn {
  stop-color: var(--svg-color--a520b6, #a520b6);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.u8koxhvda {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.977 13.74c.085-.375-.09-.75-.41-.965l-.41-.275l-1.01.5c.76 0 1.4.345 1.35.585a7.565 7.565 0 0 1-7.41 5.915A7.54 7.54 0 0 1 4.502 12c0-4.14 3.395-7.5 7.58-7.5c3.635 0 6.675 2.535 7.41 5.915c.05.25-.59.585-1.35.585l1.01.5l.4-.25a.92.92 0 0 0 .425-.975A8.07 8.07 0 0 0 12.082 4a8.04 8.04 0 0 0-8.08 8c0 4.42 3.62 8 8.085 8c3.86 0 7.09-2.68 7.89-6.26m-6.73-.18a3.15 3.15 0 0 0 1.815-2.895c0-1.75-1.365-3.165-3.07-3.165s-3.06 1.45-3.06 3.2a3.1 3.1 0 0 0 1.82 2.865l-1.165 1.01c-.24-.265-.8-.8-1.085-.865c.135.16.295.45.44.72c.155.285.3.55.4.635c.18.15 1.065.035 1.57-.55v.15l-.765 1.225a2.6 2.6 0 0 0-1.145-.425l.07.055c.135.11.265.21.43.41c.2.25.395.485.51.55c.22.115 1.185-.225 1.515-1.015l.475-.465l.46.425c.31.82 1.305 1.17 1.53 1.05c.115-.06.305-.295.51-.545c.14-.17.255-.25.37-.335l.13-.095c-.408.036-.8.17-1.145.39l-.78-1.24l.04-.115c.5.565 1.365.675 1.54.53c.105-.085.25-.35.4-.635c.15-.27.31-.56.445-.72c-.29.065-.845.6-1.085.865zm-1.205-2.96h-.08l-.135.175c-.26.34-.555.725-.935.725c-.49 0-.89-.45-.89-1c0-.52.35-.945.8-.995V9.5h2.49v.02c.4.095.71.5.71.98c0 .55-.4 1-.89 1c-.38 0-.675-.385-.935-.725z");
}

.zdxws8cls {
  stop-color: var(--svg-color--15e6fc, #15e6fc);
}

</style>
