<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fhvjqwado"/><path class="s7j_qrfsg"/><path class="j-hrxqe-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:warning-triangle" /></template>
<style>
.fhvjqwado {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.98 4.99l7.29 13.02q.98 1.74-1.02 1.74H4.75q-2 0-1.02-1.74l7.29-13.02q.98-1.74 1.96 0");
}

.j-hrxqe-r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.5h.01");
}

.s7j_qrfsg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.49 9.03l4.17 7.45q.49.87-.51.87h-8.3q-1 0-.51-.87l4.17-7.45q.49-.87.98 0M12 12v1.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
