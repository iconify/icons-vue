<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="zvb-krb3m"/><path class="qvoc8gbpg"/><path class="r82irb6gc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:route-start-sharp" /></template>
<style>
.qvoc8gbpg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 17.5h.01");
}

.r82irb6gc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 17.5h5.5v-12h5.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zvb-krb3m {
  cx: 6.5px;
  cy: 17.5px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
