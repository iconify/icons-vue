<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7qw35bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:smartphone-camera-sharp" /></template>
<style>
.x7qw35bpu {
  fill: currentColor;
  d: path("M6 22V2h12v3.5H7v13h11V22zm7.308-6.577v-5.98h2.134l.866-.866H18l.857.865H21v5.981zm3.846-1.5q.61 0 1.055-.445t.445-1.058t-.445-1.045t-1.055-.433t-1.055.433t-.445 1.045q0 .613.445 1.058t1.055.445");
}

</style>
