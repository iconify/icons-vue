<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fjhmvebfg"/><path class="r0sazqbgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:server-zap-sharp" /></template>
<style>
.fjhmvebfg {
  d: path("M3 2L19 2L19 10L3 10L3 2ZM14 22L3 22L3 14L14 14M20.2929 15.7071L17 19L21 19L17.7071 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r0sazqbgm {
  fill: currentColor;
  d: path("M8 6C8 6.5523 7.5523 7 7 7C6.4477 7 6 6.5523 6 6C6 5.4477 6.4477 5 7 5C7.5523 5 8 5.4477 8 6ZM12 6C12 6.5523 11.5523 7 11 7C10.4477 7 10 6.5523 10 6C10 5.4477 10.4477 5 11 5C11.5523 5 12 5.4477 12 6ZM8 18C8 18.5523 7.5523 19 7 19C6.4477 19 6 18.5523 6 18C6 17.4477 6.4477 17 7 17C7.5523 17 8 17.4477 8 18ZM12 18C12 18.5523 11.5523 19 11 19C10.4477 19 10 18.5523 10 18C10 17.4477 10.4477 17 11 17C11.5523 17 12 17.4477 12 18Z");
  stroke: none;
}

</style>
