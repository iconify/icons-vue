<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np-iv85qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:valve-actuator" /></template>
<style>
.np-iv85qe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.125 2.25h3.75q1.398 0 2.386.989q.989.988.989 2.386v.75q0 3.375-3.375 3.375H12.75v4.787l5.243-2.623q1.123-.561 2.19.099q1.067.659 1.067 1.914v3.646q0 1.255-1.067 1.914q-1.067.66-2.189.099l-5.659-2.83q-.335-.168-.67 0l-5.658 2.83q-1.123.561-2.19-.099q-1.067-.659-1.067-1.914v-3.646q0-1.255 1.067-1.914q1.067-.66 2.19-.099l5.243 2.623V9.75h-1.125q-3.375 0-3.375-3.375v-.75q0-1.398.989-2.386q.988-.989 2.386-.989");
}

</style>
