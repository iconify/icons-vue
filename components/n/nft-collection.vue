<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhr763yhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nft-collection" /></template>
<style>
.yhr763yhk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 1.75h1q1.76 0 3.005 1.245T11.25 6v1q0 1.76-1.245 3.005T7 11.25H6q-1.76 0-3.005-1.245T1.75 7V6q0-1.76 1.245-3.005T6 1.75m12 0h-1q-1.76 0-3.005 1.245T12.75 6v1q0 1.76 1.245 3.005T17 11.25h1q1.76 0 3.005-1.245T22.25 7V6q0-1.76-1.245-3.005T18 1.75m-12 11h1q1.76 0 3.005 1.245T11.25 17v1q0 1.76-1.245 3.005T7 22.25H6q-1.76 0-3.005-1.245T1.75 18v-1q0-1.76 1.245-3.005T6 12.75m12 0h-1q-1.76 0-3.005 1.245T12.75 17v1q0 1.76 1.245 3.005T17 22.25h1q1.76 0 3.005-1.245T22.25 18v-1q0-1.76-1.245-3.005T18 12.75m.458 3.35q.089.211.318.229q.69.054.903.714t-.314 1.108q-.173.149-.119.373q.163.672-.399 1.08t-1.153.043q-.194-.118-.391.002q-.588.363-1.15-.045t-.398-1.083q.053-.221-.122-.372q-.526-.447-.312-1.106q.213-.66.905-.714q.228-.018.317-.231q.259-.64.957-.64q.694 0 .957.64z");
}

</style>
