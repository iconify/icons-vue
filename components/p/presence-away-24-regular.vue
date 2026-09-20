<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anfjhgefy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-away-24-regular" /></template>
<style>
.anfjhgefy {
  fill: currentColor;
  d: path("M13 11.31V6.5a1.5 1.5 0 0 0-3 0V12c0 .438.191.854.524 1.139l3.5 3a1.5 1.5 0 0 0 1.952-2.278zM0 12C0 5.373 5.373 0 12 0s12 5.373 12 12s-5.373 12-12 12S0 18.627 0 12m12-9a9 9 0 1 0 0 18a9 9 0 0 0 0-18");
}

</style>
