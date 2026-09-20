<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb_3p13op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-chat-outline-rounded" /></template>
<style>
.mb_3p13op {
  fill: currentColor;
  d: path("M7 21V3zm10 0v-2.308zm-2.884-5.692h5.653v-4h-5.653zm5.846 1h-5.366l-.784.784q-.106.106-.227.128t-.227-.028t-.174-.14t-.068-.233v-5.696q0-.356.231-.585q.233-.23.576-.23h6.038q.344 0 .576.232t.232.576V15.5q0 .343-.232.576t-.576.232M7.616 22q-.667 0-1.141-.475T6 20.386V3.615q0-.666.475-1.14T7.615 2h8.77q.666 0 1.14.475T18 3.614v3.808q0 .213-.144.356t-.357.144t-.356-.144T17 7.423V3.616q0-.27-.173-.443T16.385 3h-8.77q-.269 0-.442.173T7 3.616v16.769q0 .269.173.442t.443.173h8.769q.269 0 .442-.173t.173-.442v-1.193q0-.212.144-.356t.357-.144t.356.144t.143.356v1.193q0 .666-.475 1.14t-1.14.475zm4.972-15.914q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22m1.528 9.22v-4z");
}

</style>
