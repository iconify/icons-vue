<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgp653p5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:unsubscribe-sharp" /></template>
<style>
.fgp653p5r {
  fill: currentColor;
  d: path("m12 12.116l8-5.212L19.692 6L12 11L4.308 6L4 6.904zm4.165 8.72Q15 19.67 15 18t1.165-2.835T19 14t2.836 1.165T23 18t-1.164 2.836T19 22t-2.835-1.164m.489-2.451h4.692v-.77h-4.692zM3 19V5h18v7.354q-.488-.177-.988-.265T19 12q-2.502 0-4.251 1.749T13 18q0 .25.017.5t.09.5z");
}

</style>
