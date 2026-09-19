<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vmpkr1jzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sonic-forces" /></template>
<style>
.vmpkr1jzb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.643 5.5l6.7 12.601l14.055-2.478l-9.914 10.266l6.7 12.601l-12.827-6.256L16.443 42.5l1.986-14.133l-12.827-6.256l14.055-2.478zm14.146 16.967l-6.344 1.118m9.648-4.54l-7.859 1.386");
}

</style>
