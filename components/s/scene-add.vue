<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5uhhp0aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scene-add" /></template>
<style>
.n5uhhp0aj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 9a3 3 0 0 0 0 6Zm5.815 3.209q-.018-.598.066-1.191q.084-.592.268-1.162q.183-.57.46-1.1q.278-.53.641-1.006q-.104 0-.209.005q-.104.005-.208.015q-.103.011-.207.026q-.103.015-.205.036t-.204.045q-.101.026-.201.056t-.198.065t-.194.076q-.097.039-.191.084t-.186.094t-.182.103q-.089.053-.176.111t-.171.12t-.164.129t-.158.136t-.151.144t-.144.151t-.136.158q-.066.08-.129.164q-.062.084-.12.171t-.111.176t-.103.182t-.094.186t-.084.191q-.04.096-.076.194t-.065.198q-.03.1-.056.201q-.025.102-.045.204q-.021.102-.036.205q-.015.104-.026.207q-.01.104-.015.208Q13 11.896 13 12q0 .225.024.449t.071.444t.118.434t.162.419q.093.206.207.4t.247.376t.285.347t.321.315M4.25 12h-2M6 8L4.5 6.5M6 16l-1.5 1.5M10 6.25v-2m0 13.5v2M18 15v6m-3-3h6");
}

</style>
