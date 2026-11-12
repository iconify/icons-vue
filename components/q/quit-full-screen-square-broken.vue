<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bc1hpiy2y"/><path class="krbrm1v9d"/><path class="e82515hbz"/><path class="u66s-fbqm"/><path class="si_mtzbvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quit-full-screen-square-broken" /></template>
<style>
.bc1hpiy2y {
  d: path("M9.99805 6.00017C9.98358 7.70673 9.88883 8.64752 9.26842 9.26793C8.64801 9.88834 7.70722 9.98309 6.00065 9.99756");
}

.e82515hbz {
  d: path("M14 6.00017C14.0145 7.70673 14.1092 8.64752 14.7296 9.26793C15.35 9.88834 16.2908 9.98309 17.9974 9.99756");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.krbrm1v9d {
  d: path("M9.99805 17.9974C9.98358 16.2908 9.88883 15.35 9.26842 14.7296C8.64801 14.1092 7.70722 14.0145 6.00065 14");
}

.si_mtzbvj {
  d: path("M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C21.5093 4.43821 21.8356 5.80655 21.9449 8");
}

.u66s-fbqm {
  d: path("M14 17.9974C14.0145 16.2908 14.1092 15.35 14.7296 14.7296C15.35 14.1092 16.2908 14.0145 17.9974 14");
}

</style>
