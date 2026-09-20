<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGcnYfLeKk)" class="r4i437pya"/><path clip-rule="evenodd" class="zvfyygb-z"/></g><defs><linearGradient id="SVGcnYfLeKk" x1="3.454" x2="9.586" y1="10.983" y2="10.983" gradientUnits="userSpaceOnUse"><stop offset=".16" class="vanysdb7t"/><stop offset="1" class="fnvtalzqw"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:thol-background" /></template>
<style>
.fnvtalzqw {
  stop-color: var(--svg-color--4412bd, #4412bd);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vanysdb7t {
  stop-color: var(--svg-color--27cad8, #27cad8);
}

.zvfyygb-z {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m8.852 7.775l2.85 2.4c.24.2.58.2.81-.005l2.734-2.4c.285-.25.3-.7.025-.965l-2.74-2.63a.615.615 0 0 0-.85-.01l-2.85 2.63a.657.657 0 0 0 .026.98zm1.495-.3l1.44 1.215c.12.1.295.1.41-.005l1.385-1.215a.334.334 0 0 0 .01-.49l-1.385-1.33a.31.31 0 0 0-.43 0l-1.44 1.325a.333.333 0 0 0 .01.5m-3.41.71l4.73 3.605a.61.61 0 0 0 .76-.01l4.454-3.585c.245-.2.59-.185.82.035l2.1 2.035a.655.655 0 0 1 0 .94l-1.36 1.31l1.34 1.33c.27.27.25.725-.045.97l-5.215 4.325a3.7 3.7 0 0 1-2.37.86h-.264c-.86 0-1.695-.3-2.365-.85l-5.235-4.33a.656.656 0 0 1-.035-.975l1.38-1.33l-1.425-1.325a.66.66 0 0 1-.025-.935L6.117 8.25a.615.615 0 0 1 .82-.065m-.17 1.445l4.735 3.73c.22.17.525.175.75.01l5.084-3.74l1.165 1.225l-6.25 4.485a.63.63 0 0 1-.75-.015l-5.87-4.47zm0 3.68l4.735 3.73c.22.175.525.18.75.01l5.084-3.74l1.1 1.23l-6.184 4.48a.615.615 0 0 1-.75-.015l-5.69-4.465z");
}

</style>
