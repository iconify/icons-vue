<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2pd6qb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:spill" /></template>
<style>
.l2pd6qb0e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.51 2.333L3.853 4.265q-.063.012-.124.036q-.06.023-.115.056t-.104.075q-.049.043-.09.093q-.041.049-.073.106t-.053.117t-.033.124T3.25 5v7q0 .065.011.128q.011.064.033.124q.022.061.053.117q.032.057.073.106q.041.05.09.093t.104.075t.115.056t.124.036l9.657 1.932q.233.087.49.087q1.274 0 1.953-2.135q.548-1.723.547-4.119q.001-2.396-.547-4.119Q15.274 2.246 14 2.246q-.257 0-.49.087M11.5 8.5q0 2.396.547 4.119q.04.124.082.242L4.75 11.385v-5.77l7.379-1.476q-.042.118-.082.242Q11.5 6.104 11.5 8.5M4.75 19.25q0-1.987 2.658-2.546q1.841-.388 4.056.025q2.453-.694 5.534-.445q4.252.343 4.252 2.716q0 2.303-3.782 2.775q-2.052.257-5.446-.021q-2.967.415-4.739.042q-2.533-.533-2.533-2.546");
}

</style>
