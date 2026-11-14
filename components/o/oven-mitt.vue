<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o21fd37sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:oven-mitt" /></template>
<style>
.o21fd37sn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.484 4.048Q6.25 5.413 6.25 8l.002.06l.656 8.196q.046-.006.092-.006h9q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H7.028l.224 2.81q.006.07.024.137q.019.068.05.131q.03.063.072.119q.042.057.093.104q.052.048.111.085t.125.062q.065.026.134.039T8 21.25h3q6.214 0 8.671-4.915q.95-1.901.039-3.463q-.745-1.278-2.31-1.549l.335-1.676q.45-2.247-.804-4.072q-1.305-1.898-3.808-2.315q-2.633-.439-4.639.788");
}

</style>
