<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2pwqzspl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:search-check-2-outline-rounded" /></template>
<style>
.h2pwqzspl {
  fill: currentColor;
  d: path("M14.567 14.56q1.799-1.805 1.799-4.385T14.564 5.79t-4.375-1.81t-4.381 1.806T4 10.171t1.806 4.387q1.805 1.807 4.384 1.807t4.377-1.805m-5.386-3.071l-1.675-1.67q-.146-.146-.344-.155t-.364.155t-.168.354t.162.354l1.818 1.817q.238.243.566.243t.57-.243l3.827-3.84q.146-.146.156-.347t-.156-.366t-.357-.166t-.356.166zm1.011 5.877q-2.984 0-5.088-2.104T3 10.173t2.104-5.088t5.088-2.104t5.08 2.104t2.094 5.088q0 1.359-.467 2.559q-.466 1.2-1.285 2.149l5.052 5.052q.146.14.146.335q0 .194-.15.359t-.357.165t-.372-.165L14.9 15.594q-.948.839-2.149 1.305q-1.2.467-2.559.467m0-7.193");
}

</style>
