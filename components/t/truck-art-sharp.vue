<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="o7vie3lcy"/><path class="pb7-hxbnd"/><path class="ywkpp0bhy"/><path class="w06evxbjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:truck-art-sharp" /></template>
<style>
.o7vie3lcy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.62 8.76l.76-4.77l.12-.74l.59.46l2.07 1.58l.59.46l.55-.51l2.15-1.98l.55-.51l.55.51l2.15 1.98l.55.51l.59-.46l2.07-1.58l.59-.46l.12.74l.76 4.77l.12.74h-15zm-.37.74h15.5v9H4.25z");
}

.pb7-hxbnd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 11.75h10v3H6.75v-3z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.w06evxbjf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 18.5V21m10-2.5V21");
}

.ywkpp0bhy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 16.5h.01m8.99 0h.01");
}

</style>
