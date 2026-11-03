<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="a-obuac0v"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:repeat-off-sharp-duotone" /></template>
<style>
.a-obuac0v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M18.5858 7L10.6569 7L10.6569 5L18.5858 5L17 3.4142L18.4142 2L21.7071 5.2929C21.8946 5.4804 22 5.7348 22 6C22 6.2652 21.8946 6.5196 21.7071 6.7071L18.4142 10L17 8.5858L18.5858 7ZM5.4142 17L18 17L18 19L5.4142 19L7 20.5858L5.5858 22L2.2929 18.7071C2.1054 18.5196 2 18.2652 2 18C2 17.7348 2.1054 17.4804 2.2929 17.2929L5.5858 14L7 15.4142L5.4142 17ZM2 13L2 6C2 5.4477 2.4477 5 3 5L6 5L6 7L4 7L4 13L2 13ZM22 11L22 16.3431L20 16.3431L20 11L22 11Z");
  stroke: none;
}

.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
