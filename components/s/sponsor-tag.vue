<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="j9_bdgucm"/><path class="fxhu6xblw"/><path class="okucqcc9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sponsor-tag" /></template>
<style>
.fxhu6xblw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 7h.01");
}

.j9_bdgucm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.25 2.75h3.5q2.5 0 2.5 2.5v3.5q0 2.5-1.77 4.27l-6.46 6.46q-1.77 1.77-3.54 0l-4.96-4.96q-1.77-1.77 0-3.54l6.46-6.46q1.77-1.77 4.27-1.77");
}

.okucqcc9g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.89 10.32l.62 1.37q.14.32.49.36l1.49.16q.35.04.09.27l-1.12 1.01q-.25.23-.18.58l.31 1.47q.07.34-.23.16l-1.31-.75q-.3-.17-.6 0l-1.31.75q-.3.18-.23-.16l.31-1.47q.07-.35-.18-.58l-1.12-1.01q-.26-.23.09-.27l1.49-.16q.35-.04.49-.36l.62-1.37q.14-.32.28 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
