<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlhb7_8mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:replace-audio-outline" /></template>
<style>
.wlhb7_8mh {
  fill: currentColor;
  d: path("M3.5 8q.95-2.725 3.288-4.362T12 2q2.05 0 3.888.875T19 5.35V2h2v6h-6V6h1.9q-.975-.975-2.25-1.487T12 4Q9.975 4 8.262 5.075T5.676 8zm4.525 12.975Q7 19.95 7 18.5t1.025-2.475T10.5 15q.4 0 .775.075t.725.25V10h5v2h-3v6.5q0 1.45-1.025 2.475T10.5 22t-2.475-1.025");
}

</style>
