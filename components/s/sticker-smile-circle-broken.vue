<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="gmqhdrbww"/><path class="th0xxsgwf"/><path class="t6qg_cbvk"/><ellipse transform="rotate(-15 8.714 11.328)" class="l5tkhob0v"/><path class="ly78vgcoq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sticker-smile-circle-broken" /></template>
<style>
.gmqhdrbww {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 12.6477 21.7004 13.2503 21.2424 13.7083L13.7083 21.2424C13.2503 21.7004 12.6477 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

.l5tkhob0v {
  cx: 8.714px;
  cy: 11.328px;
  rx: 0.5px;
  ry: 1px;
}

.ly78vgcoq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.7008 15.947C11.3779 16.2472 10.0733 16.2245 8.9126 15.9336");
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.t6qg_cbvk {
  d: path("M14.9923 9.64461C15.1353 10.1781 15.0349 10.6685 14.7682 10.7399C14.5014 10.8114 14.1693 10.4369 14.0264 9.90343C13.8835 9.36996 13.9838 8.87956 14.2505 8.80809C14.5173 8.73662 14.8494 9.11114 14.9923 9.64461Z");
}

.th0xxsgwf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 22C12 19.2071 12 17.8107 12.3928 16.688C13.0964 14.6773 14.6773 13.0964 16.688 12.3928C17.8107 12 19.2071 12 22 12");
}

</style>
