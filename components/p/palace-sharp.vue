<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kcgdpgb9p"/><path class="ot941dbdq"/><path class="j4nr7eb0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:palace-sharp" /></template>
<style>
.j4nr7eb0n {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 15.75h.01m7.99 0h.01");
}

.kcgdpgb9p {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.75V8l.22-.45l1.06-2.1l.22-.45l.22.45l1.06 2.1l.22.45v4.5h12.5V8l.22-.45l1.06-2.1l.22-.45l.22.45l1.06 2.1l.22.45v13.25H2.75z");
}

.ot941dbdq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 12.5c0-2.5 2.5-3.5 3.75-6c1.25 2.5 3.75 3.5 3.75 6Zm3.75-6V3m-1.5 18.25v-4.5h3v4.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
