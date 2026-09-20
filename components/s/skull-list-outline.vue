<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgs0wfmls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:skull-list-outline" /></template>
<style>
.pgs0wfmls {
  fill: currentColor;
  d: path("M4 18v-1.95q-1.35-.8-2.175-2.137T1 11q0-2.575 1.925-4.288T7.5 5t4.575 1.713T14 11q0 1.575-.825 2.913T11 16.05V18zm2-2h3v-1.1l.975-.575q.9-.525 1.463-1.4T12 11q0-1.725-1.35-2.863T7.5 7T4.35 8.138T3 11q0 1.05.563 1.913t1.462 1.412L6 14.9zm-.5-4q.425 0 .713-.288T6.5 11t-.288-.712T5.5 10t-.712.288T4.5 11t.288.713T5.5 12m1 2h2l-1-2zm3-2q.425 0 .713-.288T10.5 11t-.288-.712T9.5 10t-.712.288T8.5 11t.288.713T9.5 12m5.5 1v-2h7v2zm0 4v-2h7v2zm0-8V7h7v2zm-7.5 2.5");
}

</style>
