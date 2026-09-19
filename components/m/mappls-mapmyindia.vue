<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzpqnlmob"/><path class="yfdopx10r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mappls-mapmyindia" /></template>
<style>
.hzpqnlmob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4");
}

.yfdopx10r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.723 21.312v5.376h2.688M8.5 26.682v-5.37l2.688 5.376l2.688-5.368v5.368m7.204 0v-5.376h1.759c.995 0 1.802.808 1.802 1.805s-.807 1.806-1.802 1.806h-1.76m5.271 1.765v-5.376h1.76c.996 0 1.802.808 1.802 1.805s-.807 1.806-1.801 1.806h-1.76m9.694 1.176c.33.43.743.589 1.318.589h.796c.74 0 1.341-.6 1.341-1.341v-.006c0-.74-.6-1.34-1.341-1.34h-.878a1.343 1.343 0 0 1-1.342-1.343h0c0-.743.602-1.346 1.345-1.346h.792c.575 0 .988.16 1.318.59m-23.697 4.786l1.781-5.376l1.781 5.376");
}

</style>
