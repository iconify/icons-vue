<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="irxqprylq"/><path class="x4wge66qw"/><path class="brjfkfbgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:taxi" /></template>
<style>
.brjfkfbgg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 2.75h3.5q1 0 1.23.97l.54 2.31q.23.97-.77.97h-5.5q-1 0-.77-.97l.54-2.31q.23-.97 1.23-.97");
}

.irxqprylq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.75 13.75l1.85-5.4A2 2 0 0 1 7.5 7h9a2 2 0 0 1 1.9 1.35l1.85 5.4v4.75a1 1 0 0 1-1 1H4.75a1 1 0 0 1-1-1ZM6.5 19.5v1.75m11-1.75v1.75M4.25 12.5h15.5");
}

.x4wge66qw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 16h.01m8.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
