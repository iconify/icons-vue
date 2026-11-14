<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jl8jcjbbf"/><path class="zooduccqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mine-fan" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jl8jcjbbf {
  d: path("M2 12a10 10 0 1 0 20 0a10 10 0 1 0-20 0");
}

.zooduccqx {
  d: path("M10.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m.312-3.547l-.609-.762a1.43 1.43 0 0 1 .297-2.066l.583-.408a1.75 1.75 0 0 1 1.454-.257l1.088.29a1.336 1.336 0 0 1 .739 2.073l-.767 1.061a1.75 1.75 0 0 1-2.785.069m5.229 4.075l.964-.146a1.43 1.43 0 0 1 1.641 1.29l.062.708a1.75 1.75 0 0 1-.505 1.389l-.795.797a1.336 1.336 0 0 1-2.165-.397l-.535-1.194a1.75 1.75 0 0 1 1.333-2.447m-6.144 2.491l-.355.908a1.43 1.43 0 0 1-1.938.776l-.644-.301a1.75 1.75 0 0 1-.95-1.131l-.293-1.087a1.336 1.336 0 0 1 1.426-1.676l1.302.133a1.75 1.75 0 0 1 1.452 2.378");
}

</style>
