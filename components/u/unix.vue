<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGMRXg3chP)" class="c8a77sibq"/><path fill="url(#SVGNCy5esGI)" class="xrfq7_bso"/><defs><linearGradient id="SVGMRXg3chP" x1="20.1" x2="3.6" y1="12.804" y2="12.804" gradientUnits="userSpaceOnUse"><stop class="u6779ih_x"/><stop offset="1" class="jtoax-zqe"/></linearGradient><linearGradient id="SVGNCy5esGI" x1="14.894" x2="9.001" y1="13.468" y2="13.468" gradientUnits="userSpaceOnUse"><stop class="u6779ih_x"/><stop offset="1" class="jtoax-zqe"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:unix" /></template>
<style>
.c8a77sibq {
  d: path("M12 21c-5.328 0-8.4-2.766-8.4-8.166V3h4.8v9.672c0 2.4.93 4.128 3.6 4.128c2.658 0 3.6-1.752 3.6-4.128V3h4.8v9.834c0 5.4-3.072 8.166-8.4 8.166");
}

.ft5dv1b6b {
  fill: none;
}

.jtoax-zqe {
  stop-color: var(--svg-color--7d00bc, #7d00bc);
}

.u6779ih_x {
  stop-color: var(--svg-color--bd106a, #bd106a);
}

.xrfq7_bso {
  d: path("M12.001 16.2a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

</style>
