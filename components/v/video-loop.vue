<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anv87bbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:video-loop" /></template>
<style>
.anv87bbgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 11V9.75a3 3 0 0 1 3-3h12.5m-3-3l3 3l-3 3m2 3.25v1.25a3 3 0 0 1-3 3H3.75m3 3l-3-3l3-3m4.27-3.95l2.46 1.4q.52.3 0 .6l-2.46 1.4q-.52.3-.52-.3v-2.8q0-.6.52-.3");
}

</style>
