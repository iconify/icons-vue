<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psfxtab6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:padlock-heavy" /></template>
<style>
.psfxtab6q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 9.31q1.284.214 2.255 1.185Q22.25 11.74 22.25 13.5V18q0 1.76-1.245 3.005T18 22.25H6q-1.76 0-3.005-1.245T1.75 18v-4.5q0-1.76 1.245-3.005q.971-.971 2.255-1.185V8.5q0-2.796 1.977-4.773T12 1.75t4.773 1.977T18.75 8.5zM9.5 8.5v.75h5V8.5q0-1.036-.732-1.768T12 6Q9.5 6 9.5 8.5m0 7.25q0 2.5 2.5 2.5q1.036 0 1.768-.732t.732-1.768t-.732-1.768T12 13.25q-2.5 0-2.5 2.5");
}

</style>
