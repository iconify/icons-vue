<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dkepwleip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xmp-mod-player" /></template>
<style>
.dkepwleip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 10.419H28.269L24 15.603l-4.269-5.184H5.5l11.385 13.824L5.5 38.067h14.231L24 32.883l10.063 12.198l8.437-7.014l-11.385-13.824z");
}

</style>
