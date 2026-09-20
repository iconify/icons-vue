<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm3d2sbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:water-ph" /></template>
<style>
.fm3d2sbov {
  fill: currentColor;
  d: path("M11 22v-6h3.5q.6 0 1.05.45T16 17.5v1q0 .6-.45 1.05T14.5 20h-2v2zm6 0v-6h1.5v2h2v-2H22v6h-1.5v-2.5h-2V22zm-4.5-3.5h2v-1h-2zM9 21.95q-3.05-.35-5.025-2.625T2 13.8q0-2.5 1.988-5.437T10 2q4.025 3.425 6.013 6.363T18 13.8v.2h-7q-.825 0-1.412.588T9 16z");
}

</style>
