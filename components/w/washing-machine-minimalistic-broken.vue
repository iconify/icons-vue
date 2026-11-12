<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kz8j27a0y"/><path class="b-w7m1bnc"/><path class="t8oa_rbgh"/><path class="f00_0pbwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:washing-machine-minimalistic-broken" /></template>
<style>
.b-w7m1bnc {
  d: path("M17 14C17 16.7614 14.7614 19 12 19C9.23858 19 7 16.7614 7 14C7 11.2386 9.23858 9 12 9C14.7614 9 17 11.2386 17 14Z");
}

.f00_0pbwr {
  d: path("M7.23418 14.3624C8.08868 14.7895 9.06745 15.5209 10.724 15.8195C13.0859 16.2453 12.8501 14.1706 15.2121 14.5961C15.9323 14.7258 16.4181 14.9452 16.7616 15.1805");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kz8j27a0y {
  d: path("M21 14C21 17.7712 21 19.6569 19.8284 20.8284C18.6569 22 16.7712 22 13 22H11C7.22876 22 5.34315 22 4.17157 20.8284C3 19.6569 3 17.7712 3 14V10C3 6.22876 3 4.34315 4.17157 3.17157C5.34315 2 7.22876 2 11 2H13C16.7712 2 18.6569 2 19.8284 3.17157C21 4.34315 21 6.22876 21 10");
}

.t8oa_rbgh {
  d: path("M16 6H12M9 6H8");
}

</style>
