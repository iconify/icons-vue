<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voo10zbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-doorbell-visitor-outline-rounded" /></template>
<style>
.voo10zbjh {
  fill: currentColor;
  d: path("M16.934 16.566q-.434-.433-.434-1.066t.434-1.066T18 14t1.066.434q.434.433.434 1.066t-.434 1.066Q18.633 17 18 17t-1.066-.434M14.5 21.5v-.575q0-.85.975-1.388T18 19t2.525.538t.975 1.387v.575zM13.336 9.336q.548-.55.548-1.336t-.549-1.336T12 6.117t-1.336.549T10.117 8t.549 1.336T12 9.885t1.336-.55M10.115 16q0 .787.549 1.336t1.335.549t1.336-.55t.549-1.335t-.55-1.336T12 14.117t-1.336.549T10.117 16m1.095.79q-.326-.326-.326-.79t.326-.79t.789-.325t.79.326t.326.789t-.326.79t-.79.326t-.79-.326M7.5 7q0-1.894 1.303-3.197T12 2.5t3.197 1.303T16.5 7v4.5q0 .214-.143.357T16 12t-.357-.143t-.143-.357V7q0-1.506-1.044-2.503T12 3.5t-2.456.997T8.5 7v10q0 1.223.78 2.183q.782.96 1.93 1.223q.176.055.299.186q.122.131.122.308q0 .25-.192.406t-.443.088q-1.527-.356-2.511-1.559T7.5 17z");
}

</style>
