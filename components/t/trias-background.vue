<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG9M56Be0e)" class="r4i437pya"/><path clip-rule="evenodd" class="su3-am15s"/></g><defs><linearGradient id="SVG9M56Be0e" x1="8.48" x2="13.986" y1="8.661" y2="14.71" gradientUnits="userSpaceOnUse"><stop class="k-28254fe"/><stop offset=".807" class="hmyot6bsg"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:trias-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hmyot6bsg {
  stop-color: var(--svg-color--12aba9, #12aba9);
}

.k-28254fe {
  stop-color: var(--svg-color--79dce5, #79dce5);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.su3-am15s {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M13.24 4.076a.37.37 0 0 0-.5.046l-8.163 9.44a.31.31 0 0 0 .068.468l8.753 5.908c.134.09.318.082.441-.02l5.543-4.59a.31.31 0 0 0 .105-.331L17.102 7.06zm-7.955 9.537l8.573.776l.618-5.566l-1.629-3.954zm8.513 1.317l-7.88-.713l7.405 4.997zm.584.053l4.088.37l-4.546 3.765zm4.448-.144l-4.388-.397l.6-5.409l1.632-1.37zm-2.472-7.645l-1.43 1.201l-1.394-3.384z");
}

</style>
