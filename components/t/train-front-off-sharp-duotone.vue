<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="icrau9bax"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train-front-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.icrau9bax {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M21 6L21 17.3431L11.6569 8L19 8L19 3L6.6569 3L4.6569 1L20 1C20.5523 1 21 1.4477 21 2L21 4L23 4L23 6L21 6ZM18.2362 18.2363L19 19.0001L18.6181 19.0001L20.1708 22.1056L18.382 23L16.382 19L16.1715 19L7.618 19L5.618 23L3.8292 22.1056L5.382 19L4 19C3.4477 19 3 18.5523 3 18L3 6L1 6L1 4L3 4L3 3L5 5.0001L5 7.5001C5 7.7729 5.2188 7.9954 5.4916 8L8 8L17.6666 17.6667L17.8944 17.5528L18.2362 18.2363ZM10 13.5C10 12.6716 9.3284 12 8.5 12C7.6716 12 7 12.6716 7 13.5C7 14.3284 7.6716 15 8.5 15C9.3284 15 10 14.3284 10 13.5Z");
  stroke: none;
}

</style>
