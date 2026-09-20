<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogkoifmcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:propane-tank-sharp" /></template>
<style>
.ogkoifmcd {
  fill: currentColor;
  d: path("M4 13v-3q0-1.425.85-2.475T7 6.125V2h10v4.125q1.3.35 2.15 1.4T20 10v3zm4 9q-1.65 0-2.825-1.175T4 18v-3h16v3q0 1.65-1.175 2.825T16 22zM9 6h2V5h2v1h2V4H9z");
}

</style>
