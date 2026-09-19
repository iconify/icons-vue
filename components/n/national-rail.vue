<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a-9-hyb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:national-rail" /></template>
<style>
.a-9-hyb6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 20.468h39m-39 7.064h39M16.757 13.403l14.486 7.065l-14.486 7.065l14.486 7.065");
}

</style>
