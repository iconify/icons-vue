<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lrs967gey"/><path clip-rule="evenodd" class="wtmasybdt"/><path class="evprkp_6y"/><path class="wf0sp3jtj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xyo-background" /></template>
<style>
.evprkp_6y {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.667 9.238a1.306 1.306 0 1 0 0-2.612a1.306 1.306 0 0 0 0 2.612m7.093 4.407a1.573 1.573 0 1 0 0-3.147a1.573 1.573 0 0 0 0 3.147");
}

.ft5dv1b6b {
  fill: none;
}

.lrs967gey {
  fill: var(--svg-color--313b59, #313b59);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wf0sp3jtj {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.668 8.854a.921.921 0 1 0 0-1.842a.921.921 0 0 0 0 1.842m1.305 7.414a1.413 1.413 0 1 1-2.826 0a1.413 1.413 0 0 1 2.826 0m5.787-3.088a1.109 1.109 0 1 0 0-2.218a1.109 1.109 0 0 0 0 2.218");
}

.wtmasybdt {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M7.951 5h8.032L20 11.989L15.983 19H7.951L4 11.989zm.629 1.167h5.755L9.673 7.824zm-.324.303l-2.751 4.696l3.674-3.058zm8.15 5.39l-1.13-5.43l-5.401 1.654zM5 12.241l4.355-3.69v7.471zm4.855 3.814V8.393l6.586 3.831zm5.996-8.848l2.832 4.798h-1.797zm-.035 10.149l2.896-4.885h-1.925zm-5.888-.938l6.357-3.672l-1.05 5.419zm-4.367-3.077l2.662 4.653l.88-1.604zm3.055 4.824h5.478l-4.67-1.52z");
}

</style>
