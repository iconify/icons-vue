<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wm4bblblh"/><path clip-rule="evenodd" class="su70tabos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:serial-port" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.su70tabos {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 10C9 10.552 8.552 11 8 11C7.448 11 7 10.552 7 10C7 9.448 7.448 9 8 9C8.552 9 9 9.448 9 10ZM13 10C13 10.552 12.552 11 12 11C11.448 11 11 10.552 11 10C11 9.448 11.448 9 12 9C12.552 9 13 9.448 13 10ZM17 10C17 10.552 16.552 11 16 11C15.448 11 15 10.552 15 10C15 9.448 15.448 9 16 9C16.552 9 17 9.448 17 10ZM11 14C11 14.552 10.552 15 10 15C9.448 15 9 14.552 9 14C9 13.448 9.448 13 10 13C10.552 13 11 13.448 11 14ZM15 14C15 14.552 14.552 15 14 15C13.448 15 13 14.552 13 14C13 13.448 13.448 13 14 13C14.552 13 15 13.448 15 14Z");
  stroke: none;
}

.wm4bblblh {
  d: path("M2.091 9.728C1.618 7.834 3.05 6 5.001 6H18.999C20.95 6 22.383 7.834 21.909 9.728L20.409 15.728C20.075 17.063 18.875 18 17.499 18H6.501C5.125 18 3.925 17.063 3.591 15.728L2.091 9.728Z");
}

</style>
