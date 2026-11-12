<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="gmqhdrbww"/><path class="th0xxsgwf"/><path class="wbw_ixbrw"/><ellipse class="yad62e0rw"/><path class="g4gus2y6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sticker-smile-circle-2-broken" /></template>
<style>
.g4gus2y6w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.2981 16.9912C12.1994 16.997 12.1 17 12 17C10.8846 17 9.85038 16.6303 9 16");
}

.gmqhdrbww {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 12.6477 21.7004 13.2503 21.2424 13.7083L13.7083 21.2424C13.2503 21.7004 12.6477 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.th0xxsgwf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 22C12 19.2071 12 17.8107 12.3928 16.688C13.0964 14.6773 14.6773 13.0964 16.688 12.3928C17.8107 12 19.2071 12 22 12");
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
