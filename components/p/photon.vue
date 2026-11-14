<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i55gghbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:photon" /></template>
<style>
.i55gghbtv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 7.25q-1.801 0-3.216 4.526q-.022.071-.03.144q-.008.074-.001.147q.007.074.027.145q.021.071.056.136q.034.065.08.123q.047.057.103.105q.057.047.122.082t.135.058q.143.044.291.031q.149-.013.281-.083q.132-.069.228-.183q.095-.115.14-.257Q4.301 8.75 5 8.75t1.784 3.474Q8.199 16.75 10 16.75t3.216-4.526q.022-.071.03-.144q.008-.074.001-.147q-.007-.074-.027-.145q-.021-.071-.056-.136q-.034-.065-.08-.123q-.047-.057-.103-.105q-.057-.047-.122-.082t-.135-.058t-.144-.03t-.147-.001t-.145.027t-.136.056t-.123.08q-.057.047-.105.103q-.047.057-.082.122t-.058.135Q10.699 15.25 10 15.25t-1.784-3.474Q6.801 7.25 5 7.25M14.75 12q0-3.75 3.75-3.75T22.25 12t-3.75 3.75T14.75 12");
}

</style>
