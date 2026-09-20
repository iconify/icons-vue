<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6s31g2vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sensor-door-sharp" /></template>
<style>
.t6s31g2vi {
  fill: currentColor;
  d: path("M4 22V2h16v20zm11.5-8.5q.625 0 1.063-.437T17 12t-.437-1.062T15.5 10.5t-1.062.438T14 12t.438 1.063t1.062.437");
}

</style>
