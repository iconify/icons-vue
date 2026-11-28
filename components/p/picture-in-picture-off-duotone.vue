<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u3mtx89iz"/><path class="fbatecclr"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:picture-in-picture-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.fbatecclr {
  stroke-opacity: 0.4;
  d: path("M22 8V7C22 5.343 20.6569 4 19 4H9.6569M4.1285 4.128C2.8967 4.502 2 5.646 2 7V17C2 18.657 3.3432 20 5 20H8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u3mtx89iz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.7781 20.898C20.53 20.965 20.2691 21 20 21H14C12.3432 21 11 19.657 11 18V14C11 13.202 11.3115 12.477 11.8195 11.939L20.7781 20.898ZM21.2929 17.05L16.9498 12.707C16.7688 12.526 16.6569 12.276 16.6569 12C16.6569 11.448 17.1046 11 17.6569 11H20C21.6569 11 23 12.343 23 14V16.343C23 16.895 22.5523 17.343 22 17.343C21.7239 17.343 21.4739 17.231 21.2929 17.05Z");
  stroke: none;
}

</style>
