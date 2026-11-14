<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lglvm4bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:water-meter" /></template>
<style>
.lglvm4bpv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M10 5.25q-2.25 0-2.25 2.25T10 9.75h4q.932 0 1.591-.659T16.25 7.5t-.659-1.591T14 5.25zm1.443 6.248Q9 14.212 9 15.75q0 3 3 3t3-3q0-1.538-2.443-4.252q-.099-.111-.234-.175t-.284-.072t-.289.042q-.141.05-.252.15q-.029.026-.055.055");
}

</style>
