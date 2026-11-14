<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw6hscc4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:reagent-bottle-amber" /></template>
<style>
.gw6hscc4t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 1.75h-3Q8.25 1.75 8.25 4q0 1.5 1 2v1.351q-5.5.92-5.5 5.149v7q0 2.75 2.75 2.75h11q2.75 0 2.75-2.75v-7q0-4.229-5.5-5.149V6q1-.5 1-2q0-2.25-2.25-2.25m5.25 15.5H5.25v-3h13.5zm-13.5 1.5h13.5v.75q0 1.25-1.25 1.25h-11q-1.25 0-1.25-1.25zm0-6v-.25q0-3.15 4.843-3.756q.067-.008.132-.029q.065-.02.125-.052t.114-.074t.098-.093t.08-.109t.059-.122t.037-.13T10.75 8V6.25h2.5V8q0 .068.012.135t.037.13t.059.122t.08.109t.098.093q.054.042.114.074t.125.052q.065.021.132.029q4.843.606 4.843 3.756v.25z");
}

</style>
