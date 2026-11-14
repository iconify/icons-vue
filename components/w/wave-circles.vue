<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0iwtnbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wave-circles" /></template>
<style>
.d0iwtnbws {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.882 7.123Q1.75 9.101 1.75 12t3.132 4.877Q7.848 18.75 12 18.75t7.118-1.873Q22.25 14.899 22.25 12t-3.132-4.877Q16.152 5.25 12 5.25T4.882 7.123M5.75 12q0-1.688 2.002-2.78Q9.531 8.25 12 8.25t4.248.97Q18.25 10.312 18.25 12t-2.002 2.78q-1.779.97-4.248.97t-4.248-.97Q5.75 13.688 5.75 12");
}

</style>
