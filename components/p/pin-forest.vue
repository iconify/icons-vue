<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy_jcqbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-forest" /></template>
<style>
.fy_jcqbbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.733 4.281l2.84 4.102A.393.393 0 0 1 11.25 9a.5.5 0 0 0-.462.692l1.347 3.231A1.5 1.5 0 0 1 10.75 15h-6.5a1.5 1.5 0 0 1-1.385-2.077l1.347-3.231A.5.5 0 0 0 3.75 9a.393.393 0 0 1-.323-.617l2.84-4.102a1.5 1.5 0 0 1 2.466 0M7.5 15v6.5m12.376-8.324l.966 2.228a1.5 1.5 0 0 1-1.377 2.096h-1.93a1.5 1.5 0 0 1-1.377-2.096l.966-2.228a1.5 1.5 0 0 1 2.752 0M18.5 17.5v4");
}

</style>
