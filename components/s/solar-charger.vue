<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8lct-blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:solar-charger" /></template>
<style>
.k8lct-blp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.349 3H19.23a1.75 1.75 0 0 1 1.692 2.195l-1.579 6a1.75 1.75 0 0 1-1.692 1.305H4.77a1.75 1.75 0 0 1-1.692-2.195l1.579-6A1.75 1.75 0 0 1 6.349 3M3.75 7.75h16.5m-7-4.75l-2.5 9.5m0 0v7m-3.25 0h5.9m4.961-3.925l-2.27 2.145a.596.596 0 0 0 .409 1.03a.927.927 0 0 1 .829 1.342l-.079.158a.272.272 0 0 0 .436.314l2.253-2.253a.621.621 0 0 0-.439-1.061a.89.89 0 0 1-.782-1.317l.032-.058a.248.248 0 0 0-.389-.3");
}

</style>
