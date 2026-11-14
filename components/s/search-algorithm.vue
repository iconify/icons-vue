<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu44w4wuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:search-algorithm" /></template>
<style>
.iu44w4wuq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 8q0-2.589 1.831-4.419Q9.411 1.75 12 1.75t4.419 1.831T18.25 8q0 2.206-1.329 3.861l2.359 2.359q.106.105.163.243t.057.287t-.057.287t-.163.243q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-2.359-2.359Q14.206 14.25 12 14.25q-2.589 0-4.419-1.831Q5.75 10.589 5.75 8m-1.5 8.75h1q1.036 0 1.768.732t.732 1.768v.5q0 1.036-.732 1.768t-1.768.732h-1q-1.036 0-1.768-.732T1.75 19.75v-.5q0-1.036.732-1.768t1.768-.732m7.25 0q-1.036 0-1.768.732T9 19.25v.5q0 1.036.732 1.768t1.768.732h1q1.036 0 1.768-.732T15 19.75v-.5q0-1.036-.732-1.768T12.5 16.75zm7.25 0h1q1.036 0 1.768.732t.732 1.768v.5q0 1.036-.732 1.768t-1.768.732h-1q-1.036 0-1.768-.732t-.732-1.768v-.5q0-1.036.732-1.768t1.768-.732");
}

</style>
