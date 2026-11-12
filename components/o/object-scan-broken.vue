<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sthj-0bog"/><path class="x-1lf64uh"/><path class="csr3o-baz"/><path class="ros5bvrws"/><path class="lg_7281ce"/><path class="s1hfqbcfi"/><path class="cos_lwb7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:object-scan-broken" /></template>
<style>
.cos_lwb7y {
  d: path("M14 18.5C15.8856 18.5 16.8284 18.5 17.4142 17.9142C18 17.3284 18 16.3856 18 14.5V14M10 18.5C8.11438 18.5 7.17157 18.5 6.58579 17.9142C6 17.3284 6 16.3856 6 14.5V14");
}

.csr3o-baz {
  d: path("M2 10C2 9.65081 2 9.31779 2.00093 9M10 2C6.22876 2 4.34315 2 3.17157 3.17157C2.51839 3.82476 2.22938 4.69989 2.10149 6");
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

.ros5bvrws {
  d: path("M14 2C17.7712 2 19.6569 2 20.8284 3.17157C22 4.34315 22 6.22876 22 10");
}

.s1hfqbcfi {
  d: path("M6 10V9.5C6 7.61438 6 6.67157 6.58579 6.08579C7.17157 5.5 8.11438 5.5 10 5.5H14C15.8856 5.5 16.8284 5.5 17.4142 6.08579C18 6.67157 18 7.61438 18 9.5V10");
}

.sthj-0bog {
  d: path("M22 14C22 14.3492 22 14.6822 21.9991 15M14 22C17.7712 22 19.6569 22 20.8284 20.8284C21.4816 20.1752 21.7706 19.3001 21.8985 18");
}

.x-1lf64uh {
  d: path("M10 22C6.22876 22 4.34315 22 3.17157 20.8284C2 19.6569 2 17.7712 2 14");
}

</style>
