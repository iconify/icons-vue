<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t4g5kt4iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zoho-show" /></template>
<style>
.t4g5kt4iv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31 24l-10.453 6.035v-12.07zM4.5 39.5h39m-39-31h39m-4 6v23c0 1.108-.892 2-2 2m-29-6v-23c0-1.108.892-2 2-2");
}

</style>
