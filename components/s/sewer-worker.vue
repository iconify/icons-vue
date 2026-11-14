<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iru2peail"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sewer-worker" /></template>
<style>
.iru2peail {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8a6 6 0 0 1 12 0M4 8h16M7.5 8v1.5q0 .11.005.221q.006.11.017.22q.01.11.027.219q.016.11.037.218q.022.108.049.215q.027.108.059.213q.032.106.069.21t.08.206q.042.102.089.202t.099.197t.109.192t.118.187q.062.092.128.181q.065.088.135.174t.145.167q.074.082.152.16t.16.152t.167.145q.086.07.174.135q.089.066.181.128q.092.061.187.118q.094.057.192.109q.097.052.197.099t.202.089t.206.08t.21.069q.105.032.213.059q.107.027.215.049q.108.021.218.037q.109.017.219.027q.11.011.22.017Q11.89 14 12 14q.371 0 .736-.061q.366-.06.717-.18t.677-.295t.62-.402m1.078-1.196q.329-.533.501-1.136T16.5 9.5V8m-13 13.5c0-3 3.5-4.75 8.5-4.75q1.033 0 1.975.098m6.408 3.735q.116.437.117.917m.75-5.75A2.25 2.25 0 1 1 19 13.5m-1.5 3.75l-3 3");
}

</style>
