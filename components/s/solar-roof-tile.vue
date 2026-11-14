<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xb68fqbaj"/><path class="kkwhygb5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:solar-roof-tile" /></template>
<style>
.kkwhygb5j {
  d: path("M6.75 4.5L11 11h10.5M11 11v9m-.75-15.5L14.5 11m-.75-6.5L18 11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xb68fqbaj {
  d: path("M2.5 20v-9l4.25-6.5h10.5L21.5 11v9Z");
}

</style>
