<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da811hbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:seed-pumpkin" /></template>
<style>
.da811hbln {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.79 10.443q-1.233-4.932-5.387-7.576q-.091-.057-.193-.087T12 2.75t-.21.03t-.193.087Q7.443 5.511 6.21 10.443q-1.12 4.481.605 8.362l.014.03Q8.161 21.5 12 21.5t5.171-2.665l.014-.03q1.725-3.881.605-8.362m-5.285-3.998q2.118 1.926 2.642 5.186q.461 2.869-.451 5.148q-.011.029-.025.056q-.77 1.54-2.671 1.54t-2.671-1.54q-.014-.027-.025-.056q-.912-2.279-.451-5.148q.524-3.26 2.642-5.186q.052-.047.111-.083t.124-.062t.132-.037q.069-.013.138-.013t.138.013q.068.012.132.037q.065.025.124.062q.059.036.111.083");
}

</style>
