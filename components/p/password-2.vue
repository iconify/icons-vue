<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj2ju6bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:password-2" /></template>
<style>
.vj2ju6bij {
  fill: currentColor;
  d: path("M4 13q-1.25 0-2.125-.875T1 10t.875-2.125T4 7t2.125.875T7 10t-.875 2.125T4 13m-2 6v-2h20v2zm7.875-6.875Q9 11.25 9 10t.875-2.125T12 7t2.125.875T15 10t-.875 2.125T12 13t-2.125-.875m8 0Q17 11.25 17 10t.875-2.125T20 7t2.125.875T23 10t-.875 2.125T20 13t-2.125-.875");
}

</style>
