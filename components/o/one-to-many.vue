<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlo_f3bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:one-to-many" /></template>
<style>
.nlo_f3bnl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 2.25q-2.75 0-2.75 2.75q0 .845.259 1.43l-4.82 4.82H8.201Q7.85 8.75 5 8.75q-3.25 0-3.25 3.25T5 15.25q2.85 0 3.201-2.5h3.488l4.82 4.82q-.259.585-.259 1.43q0 2.75 2.75 2.75T21.75 19T19 16.25q-.845 0-1.43.259l-3.759-3.759h2.499q.345 2 2.69 2q2.75 0 2.75-2.75T19 9.25q-2.345 0-2.69 2h-2.499l3.759-3.759q.585.259 1.43.259q2.75 0 2.75-2.75T19 2.25");
}

</style>
