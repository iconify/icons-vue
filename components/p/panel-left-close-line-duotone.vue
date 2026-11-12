<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j-3yojbro"/><path class="vbwan82rd"/><path class="v3-yjpbpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-left-close-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-3yojbro {
  d: path("M14 3L10 3C6.22877 3 4.34315 3 3.17158 4.17157C2 5.34314 2 7.22876 2 11L2 13C2 16.7712 2 18.6569 3.17157 19.8284C4.34315 21 6.22876 21 10 21L14 21C17.7712 21 19.6569 21 20.8284 19.8284C22 18.6569 22 16.7712 22 13L22 11C22 7.22876 22 5.34315 20.8284 4.17157C19.6569 3 17.7712 3 14 3Z");
}

.v3-yjpbpv {
  stroke-linejoin: round;
  d: path("M16.7832 15L14.2118 12L16.7832 9");
}

.vbwan82rd {
  d: path("M9 3L9 21");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
