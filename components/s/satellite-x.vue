<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y98s33qgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:satellite-x" /></template>
<style>
.y98s33qgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.172 8.879l.707-.707a1.75 1.75 0 0 1 2.475 0l2.474 2.474a1.75 1.75 0 0 1 0 2.475l-.707.707a1.75 1.75 0 0 1-2.475 0l-2.474-2.474a1.75 1.75 0 0 1 0-2.475m-4.243 5.657l.707-.708a1.5 1.5 0 0 1 2.121 0l1.415 1.415a1.5 1.5 0 0 1 0 2.121l-.708.707a1.5 1.5 0 0 1-2.121 0l-1.414-1.414a1.5 1.5 0 0 1 0-2.121m9.899-9.9l.708-.707a1.5 1.5 0 0 1 2.121 0l1.414 1.414a1.5 1.5 0 0 1 0 2.121l-.707.708a1.5 1.5 0 0 1-2.121 0l-1.415-1.415a1.5 1.5 0 0 1 0-2.121m-6.364 9.9l1.945-1.945m3.182-3.182l1.945-1.945M15.5 15.5l5 5m0-5l-5 5");
}

</style>
