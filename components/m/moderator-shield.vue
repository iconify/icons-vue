<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x78ta5azi"/><path class="glww7ac6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moderator-shield" /></template>
<style>
.glww7ac6f {
  d: path("m12.14 7.82l.75 1.69q.14.32.49.35l1.84.19q.35.04.09.28l-1.38 1.23q-.26.23-.18.58l.38 1.8q.07.34-.23.17l-1.6-.92q-.3-.18-.6 0l-1.6.92q-.3.17-.23-.17l.38-1.8q.08-.35-.18-.58l-1.38-1.23q-.26-.24.09-.28l1.84-.19q.35-.03.49-.35l.75-1.69q.14-.32.28 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x78ta5azi {
  d: path("M11.3 3.05a2 2 0 0 1 1.4 0l5.25 2a2 2 0 0 1 1.3 1.85v4.35c0 4.75-3.1 8.4-7.25 10c-4.15-1.6-7.25-5.25-7.25-10V6.9a2 2 0 0 1 1.3-1.85Z");
}

</style>
