<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vjoh_-drq"/><path class="c0s4vnb_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pumpkin-sharp" /></template>
<style>
.c0s4vnb_c {
  d: path("M12 7V3.5l1.5-.75m-4.75 4.5C7.25 9.25 7 11.5 7 13.75s.5 4.5 1.75 6m6.5-12.5c1.5 2 1.75 4.25 1.75 6.5s-.5 4.5-1.75 6");
}

.vjoh_-drq {
  d: path("M12 7c1.5-.75 3.5-1 5.25-.25c2.75 1.25 4 4 4 7s-1.5 6-4.5 6.75l-2.386.682L12 20l-2.364 1.182L7.25 20.5c-3-.75-4.5-3.5-4.5-6.75s1.25-5.75 4-7C8.5 6 10.5 6.25 12 7Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
