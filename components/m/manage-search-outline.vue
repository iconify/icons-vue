<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbka8m1qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:manage-search-outline" /></template>
<style>
.nbka8m1qy {
  fill: currentColor;
  d: path("M2 19v-2h10v2zm0-5v-2h5v2zm0-5V7h5v2zm18.6 10l-3.85-3.85q-.6.425-1.312.638T14 16q-2.075 0-3.537-1.463T9 11t1.463-3.537T14 6t3.538 1.463T19 11q0 .725-.213 1.438t-.637 1.312L22 17.6zM14 14q1.25 0 2.125-.875T17 11t-.875-2.125T14 8t-2.125.875T11 11t.875 2.125T14 14");
}

</style>
