<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xqun_ubql"/><path clip-rule="evenodd" class="ual22jnhh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:oven-off-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ual22jnhh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 6C13 6.5523 12.5523 7 12 7C11.4477 7 11 6.5523 11 6C11 5.4477 11.4477 5 12 5C12.5523 5 13 5.4477 13 6ZM17 6C17 6.5523 16.5523 7 16 7C15.4477 7 15 6.5523 15 6C15 5.4477 15.4477 5 16 5C16.5523 5 17 5.4477 17 6Z");
  stroke: none;
}

.xqun_ubql {
  d: path("M20 20L20 22L4 22L4 4M4 10L10 10M8 14L14 14M6.6569 2L20 2L20 15.3431M14.6569 10L20 10M1.7071 1.7071L22.2929 22.2929");
}

</style>
