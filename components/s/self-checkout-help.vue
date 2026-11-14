<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf0s4nbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:self-checkout-help" /></template>
<style>
.gf0s4nbdw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 12.5h7A1.75 1.75 0 0 1 13 14.25v5.5a1.75 1.75 0 0 1-1.75 1.75h-7a1.75 1.75 0 0 1-1.75-1.75v-5.5a1.75 1.75 0 0 1 1.75-1.75m.724-8.727l3.628-.558a1.5 1.5 0 0 1 1.694 1.168l.855 3.989a1.5 1.5 0 0 1-1.307 1.805l-3.912.42a1.5 1.5 0 0 1-1.643-1.272l-.57-3.849a1.5 1.5 0 0 1 1.255-1.703M13 14.5h5.5m0 0v-10m-.25-2h.5A1.25 1.25 0 0 1 20 3.75A1.25 1.25 0 0 1 18.75 5h-.5A1.25 1.25 0 0 1 17 3.75a1.25 1.25 0 0 1 1.25-1.25M4.5 15.5H11m4.25-12.75l-1.5-.5m1.5 3.25l-1.5.75m7.75.25l.25.5");
}

</style>
