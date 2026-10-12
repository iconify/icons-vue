<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fbzeghb4q"/><path class="f49sy0bbw"/><path class="hc7_vbkcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tuxedo" /></template>
<style>
.f49sy0bbw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.62 5.67l-.99-.84q-.38-.33-.38.17v2q0 .5.38.17l.99-.84l.76-.66l.99-.84q.38-.33.38.17v2q0 .5-.38.17l-.99-.84zM7 3.5c.6 4.25 1.5 7.75 3 11m7-11c-.6 4.25-1.5 7.75-3 11");
}

.fbzeghb4q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 3.25h5.5q1.5 0 2.77.79l1.46.92q1.27.79 1.37 2.29l.8 12q.1 1.5-1.4 1.5H4.25q-1.5 0-1.4-1.5l.8-12q.1-1.5 1.37-2.29l1.46-.92q1.27-.79 2.77-.79");
}

.hc7_vbkcy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10.75h.01M12 14h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
