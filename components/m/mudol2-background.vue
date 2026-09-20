<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="slo1ux4wh"/><path class="ffl4ibcrb"/><path class="dssmbcbkm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mudol2-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.dssmbcbkm {
  fill: var(--svg-color--f95d33, #f95d33);
  d: path("m12 4l7.11 4v.067L16.88 9.31L12 6.622L7.11 9.307v5.377L12 17.37l4.875-2.68l2.236 1.302v.01L12 20l-7.111-4V8z");
}

.ffl4ibcrb {
  fill: var(--svg-color--f95d33, #f95d33);
  d: path("M8.89 11.339v2.475L12 12.17l4.89 2.71v-2.71L12 9.587z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.slo1ux4wh {
  fill: var(--svg-color--3c7547, #3c7547);
  d: path("M12 12.085L7.111 14.75l4.89 2.934l4.888-2.934z");
}

</style>
