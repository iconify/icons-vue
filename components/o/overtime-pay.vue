<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3j6heb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:overtime-pay" /></template>
<style>
.t3j6heb6n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.141 2.013q.155.03.285.119q.06.042.112.095q.051.053.092.115q.04.062.067.131t.041.141t.012.147t-.017.146t-.044.14t-.071.129q-2.459 3.567-.112 7.209q1.237 1.92 3.007 2.615H17q-2.071 0-3.536 1.464Q12 15.929 12 18t1.464 3.536q.117.116.238.224q-1.76.252-3.634-.168q-3.998-.897-6.217-4.341T2.467 9.797T6.71 3.514t7.431-1.501M22 13.993q-.566-.434-1.211-.678q.163-.024.329-.053q.155-.028.308.009q.06.014.117.039q.058.024.11.058q.053.033.099.075t.085.09t.069.104q.03.054.051.113q.021.058.032.12t.011.123m-5 .257q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906M17 17q1 0 1 1t-1 1t-1-1t1-1");
}

</style>
