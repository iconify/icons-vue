<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xik73nb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:navy-ship-sharp" /></template>
<style>
.xik73nb1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15h18.5l-2.4 4.5l-.433.751l-.867-.001H6.45l-.867.001l-.433-.751ZM8 14.5V11h1.5V8.5h3.25V11h1.5v4H8zm3-6V4.75m-2.25-1.5c.75 1.5 3.75 1.5 4.5 0M16.75 15v-3h3.5v3ZM20 12.75l1.25-.75M3 12.5h2.5V15H3z");
}

</style>
