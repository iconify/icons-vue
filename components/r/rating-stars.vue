<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxmrt-txm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rating-stars" /></template>
<style>
.rxmrt-txm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.14 3.32l.96 2.15q.14.32.49.36l2.34.24q.35.04.09.27l-1.75 1.58q-.26.23-.19.57l.49 2.31q.08.34-.23.17L12.3 9.79q-.3-.18-.6 0l-2.04 1.18q-.31.17-.23-.17l.49-2.31q.07-.34-.19-.57L7.98 6.34q-.26-.23.09-.27l2.34-.24q.35-.04.49-.36l.96-2.15q.14-.32.28 0m-5 8l.89 1.99q.15.32.49.36l2.17.23q.35.04.09.27l-1.62 1.46q-.26.24-.19.58l.46 2.14q.07.34-.24.16L7.3 17.42q-.3-.17-.6 0l-1.89 1.09q-.31.18-.24-.16l.46-2.14q.07-.34-.19-.58l-1.62-1.46q-.26-.23.09-.27l2.17-.23q.34-.04.49-.36l.89-1.99q.14-.32.28 0m10 0l.89 1.99q.15.32.49.36l2.17.23q.35.04.09.27l-1.62 1.46q-.26.24-.19.58l.46 2.14q.07.34-.24.16l-1.89-1.09q-.3-.17-.6 0l-1.89 1.09q-.31.18-.24-.16l.46-2.14q.07-.34-.19-.58l-1.62-1.46q-.26-.23.09-.27l2.17-.23q.34-.04.49-.36l.89-1.99q.14-.32.28 0");
}

</style>
