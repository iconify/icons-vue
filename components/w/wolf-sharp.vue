<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="z2nm2jbhy"/><path class="twq01qo7k"/><path class="x8dr7yu9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wolf-sharp" /></template>
<style>
.twq01qo7k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.05 3.25a2 2 0 1 0 2.1 2.6a1.75 1.75 0 0 1-2.1-2.6Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x8dr7yu9j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 8h.01");
}

.z2nm2jbhy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 20.5c-.25-3.5 0-6.5 1-9l.654-1.635L8.25 8.25l.5-3.5l.221-1.105l.679.905l1.6 2.2L14.5 4l2.893-2.314L15.35 4.75l-2.35 4c.5 1.25 1.5 2.25 2.75 3.5c1 1 1.25 2.5 1.25 4.25v4Z");
}

</style>
