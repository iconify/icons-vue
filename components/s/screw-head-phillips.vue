<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3dc2dbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:screw-head-phillips" /></template>
<style>
.p3dc2dbpe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 12q-.001 4.039 2.855 6.896T12 21.753t6.895-2.857T21.75 12q.001-4.039-2.855-6.896T12 2.247q-4.04 0-6.895 2.857Q2.249 7.961 2.25 12M12 5.75q2.25 0 2.25 2.25v1q0 .75.75.75h1q2.25 0 2.25 2.25T16 14.25h-1q-.75 0-.75.75v1q0 2.25-2.25 2.25T9.75 16v-1q0-.75-.75-.75H8q-2.25 0-2.25-2.25T8 9.75h1q.75 0 .75-.75V8q0-2.25 2.25-2.25");
}

</style>
