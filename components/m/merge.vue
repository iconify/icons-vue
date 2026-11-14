<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdx_x-b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:merge" /></template>
<style>
.jdx_x-b9e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.125 2.75h.75q3.182 0 3.364 3H9.5q2.75 0 2.75 2.75v2.75h1.56q.214-1.284 1.185-2.255Q16.24 7.75 18 7.75t3.005 1.245T22.25 12t-1.245 3.005T18 16.25t-3.005-1.245q-.971-.971-1.185-2.255h-1.56v2.75q0 2.75-2.75 2.75h-.261q-.182 3-3.364 3h-.75q-3.375 0-3.375-3.375v-.75q0-1.398.989-2.386q.988-.989 2.386-.989h.75q3.182 0 3.364 3H9.5q1.25 0 1.25-1.25v-7q0-1.25-1.25-1.25h-.261q-.182 3-3.364 3h-.75q-3.375 0-3.375-3.375v-.75q0-3.375 3.375-3.375");
}

</style>
