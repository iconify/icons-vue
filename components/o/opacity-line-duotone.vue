<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pabt6zbew"/><path class="og90g6vjw"/><path class="clmrv0bim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:opacity-line-duotone" /></template>
<style>
.clmrv0bim {
  d: path("M7.59717 10.7594C8.63949 9.27206 9.87212 7.84913 10.9638 6.68774");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.og90g6vjw {
  stroke-linejoin: round;
  d: path("M3.40942 13.9758C3.40956 13.9759 6.77726 16.0608 12.0193 16.0608C17.2542 16.0608 20.4905 13.976 20.4995 13.9702C20.0581 18.4806 16.4007 22 11.9542 22C7.50953 22 3.8533 18.4835 3.40942 13.9758Z");
}

.pabt6zbew {
  d: path("M20.5443 13.0521C20.5443 13.3621 20.5291 13.6684 20.4996 13.9702C20.0583 18.4807 16.4008 22 11.9543 22C7.21013 22 3.36426 17.9939 3.36426 13.0521C3.36426 9.96011 6.72709 5.83321 9.24461 3.17693C10.735 1.60443 13.1736 1.60443 14.6639 3.17693C17.1814 5.83321 20.5443 9.96011 20.5443 13.0521Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
