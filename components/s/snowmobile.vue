<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="add2-8wsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:snowmobile" /></template>
<style>
.add2-8wsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.5h3.75q.75 0 1.09.67l.07.16q.34.67 1.09.67h.75q.75 0 1.19-.61l1.12-1.53q.44-.61 1.19-.61h.75q.75 0 1.37.43l4.51 3.14q.62.43.17 1.03l-.6.8q-.45.6-1.2.6H4.25q-.75 0-.87-.74l-.51-3.27q-.12-.74.63-.74m11.25-1.25L13 4.75m-1 9.5v5.5m-7.25 0H18.5A2.75 2.75 0 0 0 21.25 17");
}

</style>
