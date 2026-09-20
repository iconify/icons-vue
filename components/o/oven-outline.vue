<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_quun51e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:oven-outline" /></template>
<style>
.v_quun51e {
  fill: currentColor;
  d: path("M16.713 7.097Q17 6.809 17 6.385t-.287-.713T16 5.384t-.712.288t-.288.713t.288.712t.712.288t.713-.288m-4 0Q13 6.809 13 6.385t-.287-.713T12 5.384t-.712.288t-.288.713t.288.712t.712.288t.713-.288m-4 0Q9 6.809 9 6.385t-.287-.713T8 5.384t-.712.288T7 6.385t.288.712t.712.288t.713-.288M5 9.616v8.769q0 .23.192.423t.423.192h12.77q.23 0 .423-.192t.192-.423v-8.77zm5.385 3.615h3.23V12h-3.23zM5.615 20q-.69 0-1.152-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zM12 9.616");
}

</style>
