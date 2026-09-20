<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6yefkbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-golf-outline" /></template>
<style>
.m6yefkbry {
  fill: currentColor;
  d: path("M7.749 13.255Q6 11.509 6 9.004t1.745-4.255T11.996 3t4.255 1.745Q18 6.491 18 8.996t-1.745 4.255T12.004 15t-4.255-1.745m7.789-.717Q17 11.075 17 9t-1.463-3.537T12 4T8.463 5.463T7 9t1.463 3.538T12 14t3.538-1.463m-4.826-3.825Q11 8.425 11 8t-.288-.712T10 7t-.712.288T9 8t.288.713T10 9t.713-.288m4 0Q15 8.426 15 8t-.288-.712T14 7t-.712.288T13 8t.288.713T14 9t.713-.288m-2-2Q13 6.426 13 6t-.288-.712T12 5t-.712.288T11 6t.288.713T12 7t.713-.288M11.5 20.886v-1q0-1.056-.722-1.778T9 17.385H7.77v-1h8.46v1H15q-1.056 0-1.778.722t-.722 1.778v1zM12 9");
}

</style>
