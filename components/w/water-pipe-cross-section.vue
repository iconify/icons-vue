<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpinbzbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:water-pipe-cross-section" /></template>
<style>
.kpinbzbrx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m6.031-.586q2.344-1.874 4.688 0q1.406 1.126 2.812 0q.058-.046.124-.08q.065-.034.136-.054q.071-.021.145-.027q.073-.007.147.002q.073.008.144.03t.135.058t.121.083t.103.105q.079.1.122.221q.042.12.042.248q0 1.864-1.318 3.182T12 16.5t-3.182-1.318T7.5 12q0-.084.019-.167q.018-.082.055-.158t.089-.142t.118-.119");
}

</style>
