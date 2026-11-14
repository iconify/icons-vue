<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uixnkpows"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:marker-square" /></template>
<style>
.uixnkpows {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.375 2.75H6.625q-3.375 0-3.375 3.375v7.75q0 3.375 3.375 3.375h1.153q1.052 0 1.6.897l.607.994q.69 1.131 2.015 1.131t2.015-1.131l.607-.994q.548-.897 1.6-.897h1.153q3.375 0 3.375-3.375v-7.75q0-3.375-3.375-3.375m-6.125 4h1.5q1.036 0 1.768.732t.732 1.768v1.5q0 1.036-.732 1.768t-1.768.732h-1.5q-1.036 0-1.768-.732T8.75 10.75v-1.5q0-2.5 2.5-2.5");
}

</style>
