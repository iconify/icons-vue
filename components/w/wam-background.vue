<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="eu-90--wy"/><path class="sjvmx0byi"/><path class="drf4q4b-f"/><path class="gaqqnsnce"/><path class="rx9eysb4r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wam-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.drf4q4b-f {
  fill: var(--svg-color--221e20, #221e20);
  d: path("M14.368 16.002H9.913l-.4-1.1c-.05-.135.05-.28.2-.3l5.005-.6c.18-.02.325.14.265.3zm-3.87-5l-1-2.5h-1.75a.25.25 0 0 0-.235.33l1.235 4.17l6.75-1l.985-3.165a.25.25 0 0 0-.235-.335h-1.75l-1 2.5l-.64-2.32a.25.25 0 0 0-.24-.18h-1.12a.25.25 0 0 0-.24.18zm-.499 3.25a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m2.765-.885a.5.5 0 1 1-1 0a.5.5 0 0 1 1 0M15 13.002a.5.5 0 1 1-1 0a.5.5 0 0 1 1 0");
}

.eu-90--wy {
  fill: var(--svg-color--ffcd00, #ffcd00);
  d: path("M11.999 19.502a7.5 7.5 0 1 0 0-15a7.5 7.5 0 0 0 0 15");
}

.ft5dv1b6b {
  fill: none;
}

.gaqqnsnce {
  fill: var(--svg-color--2e2720, #2e2720);
  d: path("M18.999 12a7.001 7.001 0 1 1-13.37-2.91a.525.525 0 0 0-.1-.6c-.235-.24-.635-.185-.775.12a8 8 0 1 0 4.11-3.97a.48.48 0 0 0-.2.71c.14.21.415.28.65.185A7 7 0 0 1 18.999 12");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rx9eysb4r {
  fill: var(--svg-color--2e2720, #2e2720);
  d: path("M7.649 6.514a.526.526 0 0 0 .125-.7a.475.475 0 0 0-.69-.125q-.653.508-1.19 1.14a.475.475 0 0 0 .035.645c.215.215.57.185.77-.05c.285-.33.605-.635.95-.91");
}

.sjvmx0byi {
  fill: var(--svg-color--fcb501, #fcb501);
  d: path("M10.634 18.637a8 8 0 0 0 8-8c0-1.95-.97-3.75-2.135-5.135c1.75 1.465 3.135 3.67 3.135 6.135a8 8 0 0 1-8 8c-2.465 0-4.67-1.385-6.135-3.135c1.39 1.165 3.18 2.135 5.135 2.135");
}

</style>
