<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q1eencbqb"/><path class="vt-cbob7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wallet-transfer" /></template>
<style>
.q1eencbqb {
  d: path("M12.2 17.5H2.5V4h19v10.6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vt-cbob7l {
  d: path("M21.5 8h-4q-.111 0-.221.011t-.218.032t-.214.054t-.208.074q-.102.043-.2.095q-.097.052-.189.113t-.177.132t-.164.148t-.148.164q-.07.085-.132.177q-.061.092-.113.189q-.052.098-.095.2q-.042.102-.074.208t-.054.214t-.032.218t-.011.221q0 .099.009.197q.008.099.026.196t.042.192q.026.096.06.189q.034.092.076.182q.042.089.092.175t.106.166q.057.08.121.156q.064.075.134.145t.146.132q.076.064.157.12t.167.105t.176.09t.182.074t.189.058t.193.042m2.31.031H21.5M15 18h6m-2.75-2.75L21 18l-2.75 2.75");
}

</style>
