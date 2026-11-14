<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgxqdkb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-plumber" /></template>
<style>
.pgxqdkb1w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.667 9.616l-.216-1.943q-.12-1.075.645-1.839l2.407-2.407q1.502-1.502 3.004 0t0 3.004l-.085.086q-.533.533-.003 1.064q.53.53 1.061 0l.092-.091q1.499-1.499 3.001.003t0 3.004l-2.407 2.407q-.764.765-1.839.645l-1.943-.216q-.179-.019-.346-.064q-.198.426-.624.852l-6.011 6.01q-1.59 1.591-3.181 0l-.353-.353q-1.591-1.59 0-3.181l6.01-6.011q.426-.426.852-.624q-.045-.167-.064-.346");
}

</style>
