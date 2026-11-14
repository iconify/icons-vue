<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smhcp5bcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scene-add" /></template>
<style>
.smhcp5bcj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 9a3 3 0 0 0 0 6Zm5.907 4.151q-.058-.353-.081-.71q-.023-.358-.008-.715q.014-.358.064-.713q.051-.354.137-.702q.086-.347.208-.684q.121-.337.276-.659q.155-.323.342-.628q.188-.306.405-.59q-.104 0-.209.005q-.104.005-.208.015q-.103.011-.207.026q-.103.015-.205.036t-.204.045q-.101.026-.201.056t-.198.065t-.194.076q-.097.039-.191.084t-.186.094t-.182.103q-.089.053-.176.111t-.171.12t-.164.129t-.158.136t-.151.144t-.144.151t-.136.158q-.066.08-.129.164q-.062.084-.12.171t-.111.176t-.103.182t-.094.186t-.084.191q-.04.096-.076.194t-.065.198q-.03.1-.056.201q-.025.102-.045.204q-.021.102-.036.205q-.015.104-.026.207q-.01.104-.015.208Q13 11.896 13 12q0 .232.025.463q.025.23.076.457q.05.226.124.446q.075.219.173.429q.098.211.218.409t.262.382q.141.184.301.352t.338.317M4.25 12h-2M6 8L4.5 6.5M6 16l-1.5 1.5M10 6.25v-2m0 13.5v2M18 15v6m-3-3h6");
}

</style>
