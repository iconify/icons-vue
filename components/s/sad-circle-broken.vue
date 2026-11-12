<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="bx61cb_8u"/><path class="cqckg2p7n"/><path class="wbw_ixbrw"/><ellipse class="yad62e0rw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sad-circle-broken" /></template>
<style>
.bx61cb_8u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 17C9.85038 16.3697 10.8846 16 12 16C13.1154 16 14.1496 16.3697 15 17");
}

.cqckg2p7n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.wbw_ixbrw {
  d: path("M15.5 10.5C15.5 11.0523 15.2761 11.5 15 11.5C14.7239 11.5 14.5 11.0523 14.5 10.5C14.5 9.94772 14.7239 9.5 15 9.5C15.2761 9.5 15.5 9.94772 15.5 10.5Z");
}

.yad62e0rw {
  cx: 9px;
  cy: 10.5px;
  rx: 0.5px;
  ry: 1px;
}

</style>
