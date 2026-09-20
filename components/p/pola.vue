<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ukf8ulb8d"/><path class="slnny_-um"/><path class="q2oumpi1c"/><path class="xx8ht_bvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pola" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.q2oumpi1c {
  fill: var(--svg-color--0d64ce, #0d64ce);
  d: path("m9.882 3.53l.953 1.588l-2.277 4.235L12 15.176h-1.77L6.706 9.353z");
}

.slnny_-um {
  fill: var(--svg-color--0b61ce, #0b61ce);
  d: path("M4.853 13.058H3l4.451 7.405l6.667.007l-.937-1.588H8.294z");
}

.ukf8ulb8d {
  fill: var(--svg-color--1b7eff, #1b7eff);
  d: path("m14.118 20.47l-.953-1.587l2.276-4.236L12 8.824h1.77l3.524 5.823z");
}

.xx8ht_bvs {
  fill: var(--svg-color--1b7ff6, #1b7ff6);
  d: path("M19.147 10.941H21l-4.451-7.405l-6.667-.007l.937 1.589h4.887z");
}

</style>
