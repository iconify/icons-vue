<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="za6ecwb3v"/><path class="cule_n21z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tennis-grip-tape" /></template>
<style>
.cule_n21z {
  d: path("m5.99 15.182l2.828 2.828a1.5 1.5 0 0 1 0 2.122a1.5 1.5 0 0 1-2.121 0l-2.829-2.829a1.5 1.5 0 0 1 0-2.121a1.5 1.5 0 0 1 2.122 0m7.071-7.778l4.949 2.121m-8.131 1.061l4.949 2.121");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.za6ecwb3v {
  d: path("M18.718 5.282za2.5 2.5 0 0 1 0 3.536l-7.779 7.778a2.5 2.5 0 0 1-3.535 0a2.5 2.5 0 0 1 0-3.535l7.778-7.779a2.5 2.5 0 0 1 3.536 0");
}

</style>
