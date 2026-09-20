<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG21Z2JbIv)" class="qd1nqlb-g"/><defs><linearGradient id="SVG21Z2JbIv" x1="18.271" x2="4.636" y1="8.183" y2="16.91" gradientUnits="userSpaceOnUse"><stop class="yaob_zb7s"/><stop offset=".49" class="hkzli6b-b"/><stop offset="1" class="rv7l3y4gm"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:welt" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hkzli6b-b {
  stop-color: var(--svg-color--b041ad, #b041ad);
}

.qd1nqlb-g {
  d: path("M19.187 3.493a1.09 1.09 0 0 1-.014 1.218q-.124.18-.308.298L6.321 13.19a1.092 1.092 0 0 1-1.189-1.832l12.544-8.181a1.09 1.09 0 0 1 1.511.321zm-5.28 16.144a1.363 1.363 0 1 1-2.726 0a1.363 1.363 0 0 1 2.727 0m4.964-9.447a1.093 1.093 0 0 0-1.2-1.827L5.127 16.544a1.092 1.092 0 1 0 1.2 1.827z");
}

.rv7l3y4gm {
  stop-color: var(--svg-color--7f67cf, #7f67cf);
}

.yaob_zb7s {
  stop-color: var(--svg-color--cd5792, #cd5792);
}

</style>
