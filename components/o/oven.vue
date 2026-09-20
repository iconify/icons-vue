<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftwj8pb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:oven" /></template>
<style>
.ftwj8pb8c {
  fill: currentColor;
  d: path("M4 8.846v-3.23q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v3.23zM5.616 20q-.691 0-1.153-.462T4 18.384V9.616h16v8.769q0 .69-.462 1.153T18.384 20zM8.713 7.097Q9 6.81 9 6.385t-.288-.713T8 5.385t-.712.287T7 6.385t.288.712t.712.288t.713-.288m1.672 6.134h3.23V12h-3.23zm2.328-6.134Q13 6.809 13 6.385t-.287-.713T12 5.384t-.712.288t-.288.713t.288.712t.712.288t.713-.288m4 0Q17 6.809 17 6.385t-.287-.713T16 5.384t-.712.288t-.288.713t.288.712t.712.288t.713-.288");
}

</style>
