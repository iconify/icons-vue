<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pu4hjwqdv"/><path class="ekkst4bjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:souvenir" /></template>
<style>
.ekkst4bjb {
  d: path("M5.837 15.5h12.326a1.75 1.75 0 0 1 1.689 1.29l.545 2A1.75 1.75 0 0 1 18.709 21H5.291a1.75 1.75 0 0 1-1.688-2.21l.545-2a1.75 1.75 0 0 1 1.689-1.29m4.891-6.465l-1.044 1.67A1.5 1.5 0 0 0 10.956 13h2.088a1.5 1.5 0 0 0 1.272-2.295l-1.044-1.67a1.5 1.5 0 0 0-2.544 0M12 13v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pu4hjwqdv {
  d: path("M6 15.5a7.5 7.5 0 1 1 12 0");
}

</style>
