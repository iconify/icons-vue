<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ercgknd1i"/><path class="x-1lf64uh"/><path class="p79yqm6ra"/><path class="ros5bvrws"/><path class="lg_7281ce"/><path class="s1hfqbcfi"/><path class="vj2oaxbxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:object-scan-linear" /></template>
<style>
.ercgknd1i {
  d: path("M22 14C22 17.7712 22 19.6569 20.8284 20.8284C19.6569 22 17.7712 22 14 22");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lg_7281ce {
  d: path("M4 11.5C4 11.5 6.4 9.5 12 9.5C17.6 9.5 20 11.5 20 11.5");
}

.p79yqm6ra {
  d: path("M10 2C6.22876 2 4.34315 2 3.17157 3.17157C2 4.34315 2 6.22876 2 10");
}

.ros5bvrws {
  d: path("M14 2C17.7712 2 19.6569 2 20.8284 3.17157C22 4.34315 22 6.22876 22 10");
}

.s1hfqbcfi {
  d: path("M6 10V9.5C6 7.61438 6 6.67157 6.58579 6.08579C7.17157 5.5 8.11438 5.5 10 5.5H14C15.8856 5.5 16.8284 5.5 17.4142 6.08579C18 6.67157 18 7.61438 18 9.5V10");
}

.vj2oaxbxd {
  d: path("M6 14V14.5C6 16.3856 6 17.3284 6.58579 17.9142C7.17157 18.5 8.11438 18.5 10 18.5H14C15.8856 18.5 16.8284 18.5 17.4142 17.9142C18 17.3284 18 16.3856 18 14.5V14");
}

.x-1lf64uh {
  d: path("M10 22C6.22876 22 4.34315 22 3.17157 20.8284C2 19.6569 2 17.7712 2 14");
}

</style>
