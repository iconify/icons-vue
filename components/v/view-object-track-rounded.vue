<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iixgb8z1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-object-track-rounded" /></template>
<style>
.iixgb8z1f {
  fill: currentColor;
  d: path("M7.5 20q-1.45 0-2.475-1.025T4 16.5t1.025-2.475T7.5 13h11q1.45 0 2.475 1.025T22 16.5t-1.025 2.475T18.5 20zm-2-9q-1.45 0-2.475-1.025T2 7.5t1.025-2.475T5.5 4h11q1.45 0 2.475 1.025T20 7.5t-1.025 2.475T16.5 11z");
}

</style>
