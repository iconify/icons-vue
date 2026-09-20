<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1clc-b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:search-check-2-outline" /></template>
<style>
.a1clc-b6i {
  fill: currentColor;
  d: path("M14.567 14.56q1.799-1.805 1.799-4.385T14.564 5.79t-4.375-1.81t-4.381 1.806T4 10.171t1.806 4.387q1.805 1.807 4.384 1.807t4.377-1.805m-5.386-1.645l4.746-4.77l-.713-.714l-4.033 4.057l-2.029-2.023l-.714.708zm1.011 4.45q-2.984 0-5.088-2.104T3 10.173t2.104-5.088t5.088-2.105t5.08 2.104t2.094 5.088q0 1.359-.467 2.559q-.466 1.2-1.285 2.149L21 20.273l-.688.727l-5.412-5.406q-.948.839-2.149 1.305q-1.2.467-2.559.467m0-7.193");
}

</style>
