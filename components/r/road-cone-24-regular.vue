<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk_-pdb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:road-cone-24-regular" /></template>
<style>
.rk_-pdb1d {
  fill: currentColor;
  d: path("M11.184 2a1.25 1.25 0 0 0-1.208.928L5.29 20.5H2.75a.75.75 0 0 0 0 1.5h18.5a.75.75 0 0 0 0-1.5h-2.54L14.023 2.928A1.25 1.25 0 0 0 12.816 2zM6.843 20.5l.933-3.5h5.974a.75.75 0 0 0 0-1.5H8.176l.534-2h4.04a.75.75 0 0 0 0-1.5H9.11l2.266-8.5h1.248l4.533 17z");
}

</style>
