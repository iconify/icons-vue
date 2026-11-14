<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv073itvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:road-closed-sign" /></template>
<style>
.iv073itvl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.75h12q1.76 0 3.005 1.245q.636.636.947 1.407q-.043-.033-.09-.059q-.131-.072-.279-.088q-.148-.017-.292.025l-19 5.5q-.081.023-.156.065q-.074.041-.137.098t-.112.126t-.081.149q-.055-.348-.055-.718V7q0-1.76 1.245-3.005T6 2.75m-3.952 9.348q.311.771.947 1.407Q4.24 14.75 6 14.75h5.25v6.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-6.75H18q1.76 0 3.005-1.245T22.25 10.5V7q0-.37-.055-.718q-.032.079-.081.149t-.112.126q-.063.057-.137.098q-.075.042-.156.065l-19 5.5q-.144.042-.292.025q-.148-.016-.279-.088q-.047-.026-.09-.059");
}

</style>
