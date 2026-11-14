<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euwl_q4gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:party-music" /></template>
<style>
.euwl_q4gi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 12.584V5q0-.062.01-.122q.01-.061.03-.119q.02-.059.049-.113t.066-.103q.038-.049.083-.091t.096-.076t.107-.059t.116-.042l7.5-2q.144-.038.292-.018q.148.019.277.094t.22.193q.09.119.129.263q.025.095.025.193v10q0 1.346-.952 2.298T13 16.25q-3.25 0-3.25-3.25T13 9.75q.979 0 1.75.504V3.976l-6 1.6V15.5q0 3.25-3.25 3.25T2.25 15.5t3.25-3.25q1.042 0 1.75.334M17.323 22.5q-1.225 0-1.89-1.029q-.665-1.03-.161-2.147l1.177-2.606q.598-1.323 2.051-1.323t2.051 1.323l1.177 2.606q.504 1.117-.161 2.147t-1.89 1.029zm0-1.5h2.354q.408 0 .63-.343q.221-.343.053-.715l-1.177-2.606q-.199-.441-.683-.441t-.683.441l-1.177 2.606q-.168.372.053.715q.222.343.63.343");
}

</style>
