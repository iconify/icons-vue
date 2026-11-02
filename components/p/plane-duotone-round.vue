<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mvl0mcbmg"/><path class="emncae9uh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-duotone-round" /></template>
<style>
.emncae9uh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m19 8l-3 3l1.725 6.901a2 2 0 0 1-.526 1.9L17 20a1.16 1.16 0 0 1-1.784-.177L12 15l-3 2v2.293c0 .453-.18.887-.5 1.207a.58.58 0 0 1-.892-.088L6 18l-2.412-1.608A.58.58 0 0 1 3.5 15.5c.32-.32.754-.5 1.207-.5H7l2-3l-4.823-3.216A1.16 1.16 0 0 1 4 7l.2-.2a2 2 0 0 1 1.899-.525L13 8l3-3c2-2 3-2 4-1s1 2-1 4");
}

.ft5dv1b6b {
  fill: none;
}

.mvl0mcbmg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m17.107 11.307l1.589 6.352a3 3 0 0 1-.79 2.849l-.199.199a2.157 2.157 0 0 1-3.324-.329l-2.66-3.991L10 17.535v1.758c.001.355-.069.708-.206 1.036a2.7 2.7 0 0 1-.587.878a1.577 1.577 0 0 1-2.431-.241l-1.497-2.245l-2.245-1.497a1.577 1.577 0 0 1-.241-2.431c.251-.252.549-.451.878-.587A2.7 2.7 0 0 1 4.707 14h1.758l1.148-1.723l-3.991-2.66a2.163 2.163 0 0 1-.329-3.324l.199-.199a3 3 0 0 1 2.849-.79l6.352 1.589l2.6-2.6c.77-.771 1.784-1.678 2.886-1.899c.99-.197 1.836.207 2.528.899c1.951 1.952.536 3.878-1 5.414Z");
}

</style>
