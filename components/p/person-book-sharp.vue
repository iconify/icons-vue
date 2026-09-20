<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pes9wibry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:person-book-sharp" /></template>
<style>
.pes9wibry {
  fill: currentColor;
  d: path("M8.775 16.525Q7.275 17.05 6 18v2h12v-2q-1.275-.95-2.775-1.475T12 16t-3.225.525M4 22V2h16v20zm10.475-9.025Q15.5 11.95 15.5 10.5t-1.025-2.475T12 7T9.525 8.025T8.5 10.5t1.025 2.475T12 14t2.475-1.025");
}

</style>
