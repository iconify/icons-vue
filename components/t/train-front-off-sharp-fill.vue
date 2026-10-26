<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="b2p3qvjgr"/><path class="pi0-wyibt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train-front-off-sharp-fill" /></template>
<style>
.b2p3qvjgr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.1715 19L4 19C3.4477 19 3 18.5523 3 18L3 3L5 5.0001L5 7.5001C5 7.7729 5.2188 7.9954 5.4916 8L8 8L19 19.0001L16.1715 19ZM10 13.5C10 12.6716 9.3284 12 8.5 12C7.6716 12 7 12.6716 7 13.5C7 14.3284 7.6716 15 8.5 15C9.3284 15 10 14.3284 10 13.5ZM4.6569 1L20 1C20.5523 1 21 1.4477 21 2L21 17.3431L11.6569 8L19 8L19 3L6.6569 3L4.6569 1Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pi0-wyibt {
  d: path("M4 5L1 5M7 18L4.7236 22.5528M17 18L19.2764 22.5528M20 5L23 5M1.7071 1.7071L22.2929 22.2929");
}

</style>
