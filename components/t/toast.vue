<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rfafu3ils"/><path class="gh1fhfbnu"/><path class="si-9z-b2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toast" /></template>
<style>
.gh1fhfbnu {
  d: path("M7 18h10v-7c.9-.5 1.25-1.2 1.25-2.1c0-.75-.6-1.15-1.4-1.15h-9.7c-.8 0-1.4.4-1.4 1.15c0 .9.35 1.6 1.25 2.1Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rfafu3ils {
  d: path("M5 21h14a1 1 0 0 0 1-1v-8.75c.85-.75 1.25-1.75 1.25-3c0-2.1-1.65-3.5-3.75-3.5h-11c-2.1 0-3.75 1.4-3.75 3.5c0 1.25.4 2.25 1.25 3V20a1 1 0 0 0 1 1");
}

.si-9z-b2c {
  d: path("m11.22 10.96l2.21.39q.74.13.61.87l-.39 2.21q-.13.74-.87.61l-2.21-.39q-.74-.13-.61-.87l.39-2.21q.13-.74.87-.61");
}

</style>
