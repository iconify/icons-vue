<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlt8bib2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:network-hub" /></template>
<style>
.wlt8bib2g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 6.25h12q1.76 0 3.005 1.245T22.25 10.5v3q0 1.76-1.245 3.005T18 17.75H6q-1.76 0-3.005-1.245T1.75 13.5v-3q0-1.76 1.245-3.005T6 6.25m1.5 6.5q0-1.5-1.5-1.5t-1.5 1.5t1.5 1.5t1.5-1.5m2.5-1.5q-1.5 0-1.5 1.5t1.5 1.5t1.5-1.5t-1.5-1.5m5.061.439q-.44-.439-1.061-.439q-1.5 0-1.5 1.5t1.5 1.5q.621 0 1.061-.439q.439-.44.439-1.061t-.439-1.061M18 11.25q-1.5 0-1.5 1.5t1.5 1.5t1.5-1.5t-1.5-1.5");
}

</style>
