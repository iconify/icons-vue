<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6twsg77z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wildfire-smoke-sky" /></template>
<style>
.x6twsg77z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.363 10.041q1.053 1.144 2.606 1.208L8 11.25h8.5q.051 0 .101-.007q3.493-.476 3.017-3.969q-.438-3.212-3.426-3.068q-1.263-2.283-3.991-2.465q-2.794-.186-4.357 2.014q-1.28.082-2.26.983Q4.44 5.791 4.376 7.344t.987 2.697m10.28 3.323Q17 15.626 17 17.5q0 4.75-5 4.75T7 17.5q0-2.969 4.386-5.406q.064-.035.135-.058q.07-.023.143-.031q.074-.009.147-.002q.074.006.145.026t.137.054q.065.034.123.08t.106.102t.084.121q.061.111.083.236q.022.126.001.251q-.208 1.247.428 1.96q.545-.96 1.666-1.707q.061-.041.13-.069q.068-.028.14-.043t.147-.014t.146.015q.073.014.141.042t.129.07t.114.093q.052.053.093.114z");
}

</style>
