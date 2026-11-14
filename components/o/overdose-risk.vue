<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq9i_p0ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:overdose-risk" /></template>
<style>
.pq9i_p0ec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.5h7A1.75 1.75 0 0 1 13 4.25A1.75 1.75 0 0 1 11.25 6h-7A1.75 1.75 0 0 1 2.5 4.25A1.75 1.75 0 0 1 4.25 2.5M3.5 6v13.5q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022T5 21h5.5q.2 0 .393-.052M12 14.943V6m6.573 8.229l1.951 4.005a1.75 1.75 0 0 1-1.573 2.516h-3.902a1.75 1.75 0 0 1-1.573-2.516l1.951-4.005a1.75 1.75 0 0 1 3.146 0M17 14.25v2.5m0 2h.01");
}

</style>
