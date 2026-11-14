<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lc4ppd86c"/><path class="ox6u261la"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:press-freedom" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lc4ppd86c {
  d: path("M13.807 12.945c-1.43.215-2.909.255-4.307.055c-2.5-.5-4-1.5-3.5-4L3 8l1.75-1q.041-.102.09-.201q.05-.099.107-.193q.057-.095.121-.184q.065-.09.136-.174t.149-.162t.162-.15t.173-.136q.089-.065.184-.122q.094-.058.193-.107q.098-.05.2-.091q.102-.042.208-.075q.105-.033.212-.058q.108-.025.217-.041t.219-.023t.221-.006q.11.002.22.012t.218.03q.109.019.216.047q.106.028.21.064q.105.037.206.081t.197.097t.19.113t.18.127q.087.068.169.142t.157.154q.076.081.145.167t.13.177t.116.188t.101.196t.084.204q.038.103.068.21q.03.106.051.214c.5 2.5 2.5 3.5 5 3l5.5-2.75l-1 3.25c-.79.474-1.73.898-2.757 1.241");
}

.ox6u261la {
  d: path("M10 7.5c.25-3 3-4.75 8-5c-.25 3.5-1.5 6.25-4 8m2.25 4.5h3.5a1.75 1.75 0 0 1 1.75 1.75v3a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 16.25 15");
}

</style>
