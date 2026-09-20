<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sal46obbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:oven-sharp" /></template>
<style>
.sal46obbq {
  fill: currentColor;
  d: path("M4 8.846V4h16v4.846zM4 20V9.616h16V20zM8.713 7.097Q9 6.809 9 6.384t-.288-.712T8 5.384t-.712.288T7 6.384t.288.713t.712.287t.713-.287m1.672 6.134h3.23V12h-3.23zm2.328-6.134Q13 6.809 13 6.385t-.287-.713T12 5.384t-.712.288t-.288.713t.288.712t.712.288t.713-.288m4 0Q17 6.809 17 6.385t-.287-.713T16 5.384t-.712.288t-.288.713t.288.712t.712.288t.713-.288");
}

</style>
