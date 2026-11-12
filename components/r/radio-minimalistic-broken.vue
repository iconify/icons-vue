<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f89c2ypeq"/><circle class="vbbzsbc0t"/><path class="zyzap34-z"/><path class="znnt10poq"/><path class="jox9tccbc"/><path class="n787bfb7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:radio-minimalistic-broken" /></template>
<style>
.f89c2ypeq {
  d: path("M22 14V14C22 17.7712 22 19.6569 20.8284 20.8284C19.6569 22 17.7712 22 14 22H10C6.22876 22 4.34315 22 3.17157 20.8284C2 19.6569 2 17.7712 2 14C2 10.2288 2 8.34315 3.17157 7.17157C4.34315 6 6.22876 6 10 6H14C17.7712 6 19.6569 6 20.8284 7.17157C21.4816 7.82475 21.7706 8.69989 21.8985 10");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jox9tccbc {
  d: path("M16 17H13.5M19 17H18.5");
}

.n787bfb7v {
  d: path("M6.5 6L15 2");
}

.vbbzsbc0t {
  cx: 8px;
  cy: 14px;
  r: 3px;
}

.znnt10poq {
  d: path("M16.5 14H19M13.5 14H14");
}

.zyzap34-z {
  d: path("M13.5 11H19");
}

</style>
