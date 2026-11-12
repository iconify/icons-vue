<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s7utufbjt"/><path class="iv23kgeik"/><path class="w5kufji0i"/><path class="l0yse_bmm"/><path class="pdgfcn4hi"/><path class="s5we7yb4z"/><path class="xkf_qjbjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:toolbox-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iv23kgeik {
  d: path("M16.52 6C16.52 4.11438 16.52 3.17157 15.9342 2.58579C15.3484 2 14.4056 2 12.52 2H11.4795C9.59387 2 8.65107 2 8.06528 2.58579C7.47949 3.17157 7.47949 4.11438 7.47949 6");
}

.l0yse_bmm {
  d: path("M18.7839 12L22 12");
}

.pdgfcn4hi {
  d: path("M8.78437 12L15.0001 12");
}

.s5we7yb4z {
  d: path("M5.37839 11H8.40549C8.61447 11 8.78388 11.1694 8.78388 11.3784V13.0141C8.78388 13.1689 8.68968 13.308 8.54602 13.3655L8.01618 13.5774C7.29449 13.8661 6.4894 13.8661 5.7677 13.5774L5.23786 13.3655C5.0942 13.308 5 13.1689 5 13.0141V11.3784C5 11.1694 5.16941 11 5.37839 11Z");
}

.s7utufbjt {
  d: path("M10 18.0513H8C5.17157 18.0513 3.75736 18.0513 2.87868 17.1726C2 16.2939 2 14.8712 2 12.0256C2 9.18012 2 7.75736 2.87868 6.87868C3.75736 6 5.17157 6 8 6H16C18.8284 6 20.2426 6 21.1213 6.87868C22 7.75736 22 9.18012 22 12.0256C22 14.8712 22 16.2939 21.1213 17.1726C20.2426 18.0513 18.8284 18.0513 16 18.0513H14");
}

.w5kufji0i {
  d: path("M2 12L5 12");
}

.xkf_qjbjs {
  d: path("M15.3784 11H18.4055C18.6145 11 18.7839 11.1694 18.7839 11.3784V13.0141C18.7839 13.1689 18.6897 13.308 18.546 13.3655L18.0162 13.5774C17.2945 13.8661 16.4894 13.8661 15.7677 13.5774L15.2379 13.3655C15.0942 13.308 15 13.1689 15 13.0141V11.3784C15 11.1694 15.1694 11 15.3784 11Z");
}

</style>
