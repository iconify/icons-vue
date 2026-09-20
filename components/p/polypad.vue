<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGRmgQXd0a)" class="ll8u-obym"/><path fill="url(#SVGH75HYbLv)" class="z6wgp0bqa"/><path class="xxd7xlbom"/><path class="af2943bzh"/><defs><linearGradient id="SVGRmgQXd0a" x1="15.97" x2="8.252" y1="5.25" y2="18.872" gradientUnits="userSpaceOnUse"><stop class="uxp5lwzfo"/><stop offset="1" class="l6v58otxm"/></linearGradient><linearGradient id="SVGH75HYbLv" x1="15.925" x2="9.381" y1="4.534" y2="21.346" gradientUnits="userSpaceOnUse"><stop class="uxp5lwzfo"/><stop offset="1" class="l6v58otxm"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:polypad" /></template>
<style>
.af2943bzh {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.999 7.837L8.325 9.918l2.043 1.16l1.63-.932l1.632.926l2.075-1.154z");
}

.ft5dv1b6b {
  fill: none;
}

.l6v58otxm {
  stop-color: var(--svg-color--a873ff, #a873ff);
}

.ll8u-obym {
  d: path("M19.94 16.495v-9L12 3L4.059 7.495v9l2.647 1.487V8.998L12 5.981l5.294 3.017v6.004L12 18.009V21z");
}

.uxp5lwzfo {
  stop-color: var(--svg-color--4e4aff, #4e4aff);
}

.xxd7xlbom {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.94 7.495L12 3L4.059 7.495l2.636 1.503L12 5.981l5.304 3.017z");
}

.z6wgp0bqa {
  d: path("M15.706 9.918L12 7.838l-3.706 2.08v9l2.117 1.143v-8.984L12 10.151l1.588.926v1.843L12 13.846v2.303l3.706-2.07z");
}

</style>
