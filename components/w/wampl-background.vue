<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="j7vm36b9r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wampl-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j7vm36b9r {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 19.733h-5.867V19.2c1.334-.24 1.2-.96.87-1.856L11.467 7.2C10.133 10.085 7.2 16.672 7.2 17.867c0 1.194 1.6 1.333 2.133 1.333v.533H4V19.2c1.067 0 2-1.259 2.336-1.856L12 4.267c1.227 2.789 3.867 9.493 4.667 11.882c.8 2.39 2.56 3.051 3.333 3.051z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
