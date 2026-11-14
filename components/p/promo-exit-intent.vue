<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldl9xlc7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:promo-exit-intent" /></template>
<style>
.ldl9xlc7a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5V3H3.5v18H12v-7.5M7.5 9.75h12M17 7.25l2.5 2.5l-2.5 2.5m-2 3h3.5l3.25 3.25l-3.25 3.25H15Z");
}

</style>
