<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="hahxbdc8f"/><path class="nsuypdmbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:temple" /></template>
<style>
.hahxbdc8f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.65v-.3q0-.6.53-.89l8.19-4.42q.53-.29 1.06 0l3.44 1.87q.53.29.27.83l-.23.47q-.26.54.32.7l.59.18q.58.16.43.74l-.2.84q-.15.58-.75.58H3.35q-.6 0-.6-.6m3.5 2.1v6m3.75-6v6m3.75-6v6m-8.1.75h12.7q.4 0 .4.4v.45q0 .4.4.4h.45q.4 0 .4.4v.45q0 .4.4.4h.45q.4 0 .4.4v.45q0 .4-.4.4H3.15q-.4 0-.4-.4v-.45q0-.4.4-.4h.45q.4 0 .4-.4v-.45q0-.4.4-.4h.45q.4 0 .4-.4v-.45q0-.4.4-.4");
}

.nsuypdmbc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 7h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
