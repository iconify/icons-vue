<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv0naqhwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-vaccination" /></template>
<style>
.pv0naqhwj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.343 13.414l7.071-7.071l4.243 4.243l-7.071 7.071Zm-3.182 3.182l4.243 4.243m-2.122-2.121l3.182-3.182m7.072-7.072l3.182-3.182m-9.9 5.657l1.768 1.768m.353-3.889l1.768 1.768");
}

</style>
