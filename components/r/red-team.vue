<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="z0s239bum"/><path class="k1tww4hdi"/><path class="rrqyg0vzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:red-team" /></template>
<style>
.k1tww4hdi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.5c-2.5 0-4 2-4 4.75S9.5 17 12 17s4-2 4-4.75s-1.5-4.75-4-4.75m-2.25 3.25l1.75.75m2.75-.75l-1.75.75");
}

.rrqyg0vzr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 13.5h.01m2.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z0s239bum {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c-4.5 0-7.25 4-7.25 9v8a1.5 1.5 0 0 0 1.5 1.5h11.5a1.5 1.5 0 0 0 1.5-1.5v-8c0-5-2.75-9-7.25-9");
}

</style>
