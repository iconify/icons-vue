<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oaa_fnphv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:seed-tray-cells" /></template>
<style>
.oaa_fnphv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11h19M3 11l1.5 7.5h3L9 11l1.5 7.5h3L15 11l1.5 7.5h3L21 11M6 11V8L4.5 5.5M6 8l1.5-2.5M12 11V8l-1.5-2.5M12 8l1.5-2.5M18 11V8l-1.5-2.5M18 8l1.5-2.5");
}

</style>
