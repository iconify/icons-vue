<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bch04wr5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-options-input-settings" /></template>
<style>
.bch04wr5w {
  fill: currentColor;
  d: path("M4.616 19q-.672 0-1.144-.472T3 17.385V6.615q0-.67.472-1.143Q3.944 5 4.616 5h14.769q.67 0 1.143.472q.472.472.472 1.144v10.769q0 .67-.472 1.143q-.472.472-1.143.472zm6.884-3.115h1l.108-.885q.473-.106.889-.32t.75-.588l.853.354l.539-.834l-.708-.616q.146-.498.146-.996t-.146-.996l.708-.615l-.539-.835l-.854.354q-.332-.374-.749-.588q-.416-.214-.89-.32l-.107-.884h-1L11.392 9q-.473.106-.889.32t-.75.588L8.9 9.554l-.538.834l.707.616q-.146.498-.146.996t.146.996l-.708.615l.539.835l.854-.354q.333.374.749.588t.89.32zm-1.028-2.357q-.626-.626-.626-1.528t.626-1.528T12 9.846t1.528.626t.626 1.528t-.626 1.528t-1.528.626t-1.528-.626");
}

</style>
