<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lfnooqypl"/><path class="yirjvmx-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:zap-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lfnooqypl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.2929 2.293L2.293 13.2929C2.1055 13.4804 2.0001 13.7348 2.0001 14C2.0001 14.5523 2.4478 15 3.0001 15L9.847 15L9.0101 20.8585C9.0034 20.9054 9 20.9526 9 20.9999C9 21.5522 9.4477 21.9999 10 21.9999C10.2652 21.9999 10.5196 21.8946 10.7071 21.707L21.707 10.7071C21.8945 10.5196 21.9999 10.2652 21.9999 10C21.9999 9.4477 21.5522 9 20.9999 9L14.153 9L14.9899 3.1415C14.9966 3.0946 15 3.0474 15 3.0001C15 2.4478 14.5523 2.0001 14 2.0001C13.7348 2.0001 13.4804 2.1054 13.2929 2.293Z");
  stroke: none;
}

.yirjvmx-n {
  d: path("M14 3.0001L3.0001 14L11 14L10 20.9999L20.9999 10L13 10L14 3.0001Z");
}

</style>
