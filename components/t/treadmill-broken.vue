<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="trr-_mkon"/><path class="iwkxsrlmm"/><path class="j7_95ib_g"/><path class="la_28ccrx"/><path class="lv3m7nwfy"/><path class="lptadmbaq"/><path class="ced0ycc1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:treadmill-broken" /></template>
<style>
.ced0ycc1z {
  stroke-linejoin: round;
  d: path("M18.0449 17.1866L18.5002 14");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iwkxsrlmm {
  d: path("M11 16V14.3664C11 13.8174 10.7561 13.2967 10.3344 12.9453L9.33793 12.1149C8.61946 11.5162 8.57018 10.4298 9.2315 9.76847L10.8855 8.11449C11.4193 7.58066 11.2452 6.67647 10.5513 6.37908C9.26627 5.82836 7.79304 5.94181 6.60752 6.68276L4.5 7.99996");
}

.j7_95ib_g {
  d: path("M7 14L6.67157 14.3284C6.09351 14.9065 5.80448 15.1955 5.43694 15.3478C5.0694 15.5 4.66065 15.5 3.84315 15.5H3");
}

.la_28ccrx {
  d: path("M12.5 10H15.5");
}

.lptadmbaq {
  stroke-linejoin: round;
  d: path("M22.0007 7L20.878 7.22454C20.2122 7.35769 19.8794 7.42426 19.6614 7.6531C19.4434 7.88195 19.393 8.21764 19.2923 8.88902L19.1309 9.96539");
}

.lv3m7nwfy {
  stroke-linejoin: round;
  d: path("M11.2878 21.9996H3.08684C2.48659 21.9996 2 21.513 2 20.9128C2 20.3848 2.37943 19.9332 2.89949 19.8422L19.0559 17.0148C20.5926 16.7459 22 17.9284 22 19.4884C22 20.8753 20.8757 21.9996 19.4888 21.9996H15");
}

.trr-_mkon {
  cx: 15px;
  cy: 4px;
  r: 2px;
}

</style>
