<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1ogj50oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:smartphone-camera-outline-sharp" /></template>
<style>
.p1ogj50oh {
  fill: currentColor;
  d: path("M6 22V2h12v3.5H7v13h11V22zm1-1h10v-1.5H7zM7 4.5h10V3H7zm6.308 10.923v-5.98h2.134l.866-.866H18l.857.865H21v5.981zm3.846-1.5q.61 0 1.055-.445t.445-1.058t-.445-1.045t-1.055-.433t-1.055.433t-.445 1.045q0 .613.445 1.058t1.055.445M7 21v-1.5zM7 4.5V3z");
}

</style>
