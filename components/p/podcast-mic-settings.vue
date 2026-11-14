<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ikhl1g6lx"/><path class="jo5z78onr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:podcast-mic-settings" /></template>
<style>
.ikhl1g6lx {
  d: path("M7.5 2.5h4a1 1 0 0 1 1 1V12a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V3.5a1 1 0 0 1 1-1Z");
}

.jo5z78onr {
  d: path("M3.75 10q0 .141.007.282t.021.282t.034.28t.048.278q.028.138.062.275q.035.137.076.272t.088.268t.102.263t.114.258t.127.253q.066.124.139.245t.151.239q.078.117.163.23q.084.114.173.223q.09.109.185.213q.094.105.194.205t.205.194q.104.095.213.185q.109.089.223.173q.113.085.23.163t.239.151q.121.073.245.139q.125.067.253.127q.127.06.258.114q.13.054.263.102t.268.088t.272.076q.137.034.275.062q.139.027.278.048q.14.02.28.034t.282.021q.141.007.282.007q.498 0 .988-.086q.491-.085.959-.254t.901-.415t.816-.563m1.718-2.409q.368-.978.368-2.023M9.5 15.75v5.75m-3.5 0h7m4.372-5.661l.052-1.038h1.152l.052 1.038l.929.537l.925-.474l.576.997l-.873.564v1.074l.873.564l-.576.997l-.925-.474l-.929.537l-.052 1.038h-1.152l-.052-1.038l-.929-.537l-.925.474l-.576-.997l.873-.564v-1.074l-.873-.564l.576-.997l.925.474Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
