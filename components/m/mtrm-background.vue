<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="abbx6-baf"/><path clip-rule="evenodd" class="e4zzqe3kg"/><path class="kvm1mh9me"/><path class="z46_horjy"/><path class="a_fvv7biw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mtrm-background" /></template>
<style>
.a_fvv7biw {
  fill: var(--svg-color--030007, #030007);
  d: path("M17.436 12a5.435 5.435 0 1 1-10.87 0a5.435 5.435 0 0 1 10.87 0");
}

.abbx6-baf {
  fill: var(--svg-color--f7df53, #f7df53);
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.e4zzqe3kg {
  fill: var(--svg-color--8117c9, #8117c9);
  fill-rule: evenodd;
  d: path("M12 19.67a7.67 7.67 0 1 0 0-15.34a7.67 7.67 0 0 0 0 15.34m0 .33a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.ft5dv1b6b {
  fill: none;
}

.kvm1mh9me {
  fill: var(--svg-color--440090, #440090);
  d: path("M18.73 12a6.73 6.73 0 1 1-13.46 0a6.73 6.73 0 0 1 13.46 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.z46_horjy {
  fill: var(--svg-color--2f0065, #2f0065);
  d: path("M18.113 12a6.112 6.112 0 1 1-12.225 0a6.112 6.112 0 0 1 12.225 0");
}

</style>
