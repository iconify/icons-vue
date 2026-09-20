<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGayIbCeCK)" class="m3vp61-iw"/><defs><linearGradient id="SVGayIbCeCK" x1="12" x2="12" y1="3.003" y2="21.003" gradientUnits="userSpaceOnUse"><stop class="a0ykbrpji"/><stop offset=".59" class="e5mvy2boz"/><stop offset="1" class="oce-nccuc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:plastik" /></template>
<style>
.a0ykbrpji {
  stop-color: var(--svg-color--0440a8, #0440a8);
}

.e5mvy2boz {
  stop-color: var(--svg-color--00b4b0, #00b4b0);
}

.ft5dv1b6b {
  fill: none;
}

.m3vp61-iw {
  d: path("M21 12.003a9 9 0 1 1-2.728-6.458l-1.21 1.187a7.313 7.313 0 1 0 2.082 3.746l-4.275 4.22l-.225.213v.011A3.938 3.938 0 1 1 14.66 9.1l-1.21 1.187a2.251 2.251 0 1 0 .023 3.414l.197-.196l.095-.113l2.104-2.081v.022l2.66-2.615v-.006l1.25-1.237A8.96 8.96 0 0 1 21 12.003");
}

.oce-nccuc {
  stop-color: var(--svg-color--02bfa1, #02bfa1);
}

</style>
