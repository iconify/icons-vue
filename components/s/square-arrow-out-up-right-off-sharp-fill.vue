<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es7p34w5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-out-up-right-off-sharp-fill" /></template>
<style>
.es7p34w5j {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 7L3 7L3 21L17 21L17 17M14.1213 9.8787L14.8284 9.1716L20.8536 3.1464M12 3L21 3L21 12M1.7071 1.7071L22.2929 22.2929");
}

</style>
