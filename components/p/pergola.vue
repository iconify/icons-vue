<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnanbsbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pergola" /></template>
<style>
.nnanbsbeu {
  fill: currentColor;
  d: path("M4 20V3.5q0-.213.144-.356T4.501 3t.356.144T5 3.5V5h14V3.5q0-.213.144-.356T19.501 3t.356.144T20 3.5V20h-1V9.77H5V20zm7.5 0v-2.827H8.673v-1h6.635v1H12.5V20z");
}

</style>
