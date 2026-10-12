<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lii_hacnb"/><path class="jats-_2kl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:whiskey-glass" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jats-_2kl {
  d: path("m10.72 9.25l2.81.75q.97.25.72 1.22l-.75 2.81q-.25.97-1.22.72L9.47 14q-.97-.25-.72-1.22l.75-2.81q.25-.97 1.22-.72M7 18h10");
}

.lii_hacnb {
  d: path("M3.75 5.75h16.5L19 19.25A2 2 0 0 1 17 21H7a2 2 0 0 1-2-1.75Z");
}

</style>
