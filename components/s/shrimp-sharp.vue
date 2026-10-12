<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vdv1wmjgn"/><path class="pkwlxmd9l"/><path class="dyj5n1gta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shrimp-sharp" /></template>
<style>
.dyj5n1gta {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.75 6.25h.01");
}

.pkwlxmd9l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.68 17.75l3.39 2l.43.25l-.48.13l-3.54.99l-.48.13l.03-.5l.19-2.75l.03-.5zm1.57-12l3.088-.882L20.75 2.75m-5.35 4h3.5L21.15 9");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vdv1wmjgn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.56 4.48l-2.62-1.15l-.55-.24l-.6.02l-2.74.06l-.6.02l-.54.27l-2.35 1.16l-.54.27l-.37.47L4.1 7.33l-.37.47l-.14.58l-.54 2.33l-.14.58l.12.59l.47 2.21l.12.59l.36.48l1.3 1.72l.36.48l.53.28l1.8.94l.53.28l.6.03l1.91.08l.6.03l.55-.23l1.67-.69l.55-.23l-.3-.52l-.65-1.13l-.3-.52l-.57.19l-.62.2l-.57.19l-.6-.07l-.64-.08l-.6-.07l-.51-.31l-.57-.36l-.51-.31l-.33-.5l-.37-.57l-.33-.5l-.09-.59l-.09-.69l-.09-.59l.17-.57l.21-.68l.17-.57l.4-.45l.47-.52l.4-.45l.55-.24l.67-.28l.55-.24l.6.02l.73.02l.6.02l.54.27l.65.33l.54.27l.39-.46l2.44-2.91l.39-.46zm-8.44 3.4L6.37 5.39m-.33 6.18l-2.54-.23m4.02 4.14l-1.45 1.45");
}

</style>
