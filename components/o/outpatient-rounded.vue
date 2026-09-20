<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs06jdbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:outpatient-rounded" /></template>
<style>
.gs06jdbjp {
  fill: currentColor;
  d: path("M2 21q-.425 0-.712-.288T1 20V4q0-.425.288-.712T2 3h12q.425 0 .713.288T15 4v16q0 .425-.288.713T14 21h-4v-5H6v5zm3-8h2v-2H5zm0-4h2V7H5zm4 4h2v-2H9zm0-4h2V7H9zm7.288 2.288Q16.575 11 17 11h2.175l-.4-.4q-.275-.275-.275-.687t.3-.713q.275-.275.7-.275t.7.275l2.1 2.1q.3.3.3.7t-.3.7l-2.1 2.1q-.275.275-.687.287T18.8 14.8q-.275-.275-.288-.687t.263-.713l.4-.4H17q-.425 0-.712-.288T16 12t.288-.712");
}

</style>
