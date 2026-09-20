<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0unwfb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:psychiatry-rounded" /></template>
<style>
.m0unwfb5n {
  fill: currentColor;
  d: path("M11.643 20.356Q11.5 20.213 11.5 20v-7.398q-1.408 0-2.69-.526T6.536 10.56T5.034 8.285t-.514-2.69v-.23q0-.336.227-.563t.562-.226h.23q1.368 0 2.649.535q1.28.536 2.27 1.526q.795.795 1.288 1.806t.653 2.139q.221-.425.496-.8q.275-.373.623-.721q.984-.987 2.274-1.525T18.481 7h.23q.336 0 .562.227q.227.226.227.561v.231q0 1.4-.537 2.69q-.538 1.29-1.525 2.274q-.99.99-2.26 1.503Q13.908 15 12.5 15v5q0 .213-.144.356t-.357.144t-.356-.144");
}

</style>
