<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iquub8bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:news-alert-off" /></template>
<style>
.iquub8bac {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.541 15.5H4.5l2-2.5v-2.598m2.086-5.714q.362-.287.766-.509q.405-.222.841-.374q.436-.151.891-.228T12 3.5q.135 0 .27.007q.135.006.269.019q.134.014.268.034q.134.019.266.046q.132.026.263.059t.261.072t.256.085q.127.045.252.097q.124.051.247.109q.122.058.241.121q.119.064.235.133q.115.07.228.145q.112.075.22.155q.109.081.213.166q.105.086.205.177q.1.09.195.186q.096.095.186.195q.091.1.177.205t.166.213t.155.22q.075.113.145.228q.069.116.133.235q.063.119.121.241q.058.123.109.247q.052.125.097.252t.085.256t.072.261t.059.263q.027.132.046.266q.02.134.034.268q.013.134.019.269q.007.135.007.27v4l2 2.5h-.059M10 18.5a2 2 0 0 0 4 0M3.5 3.5l17 17");
}

</style>
