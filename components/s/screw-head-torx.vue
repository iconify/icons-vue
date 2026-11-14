<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w14jmwb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:screw-head-torx" /></template>
<style>
.w14jmwb0t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 12q-.001 4.039 2.855 6.896T12 21.753t6.895-2.857T21.75 12q.001-4.039-2.855-6.896T12 2.247q-4.04 0-6.895 2.857Q2.249 7.961 2.25 12m11.205-4.545l.385.636q.213.353.626.361l.744.016q.957.02 1.436.849t.018 1.669l-.359.653q-.199.361 0 .722l.359.652q.461.841-.018 1.67t-1.436.849l-.744.016q-.413.008-.626.361l-.385.636q-.497.82-1.454.82q-.958 0-1.454-.819l-.386-.636q-.214-.354-.627-.362l-.744-.016q-.957-.02-1.436-.849t-.018-1.669l.359-.653q.199-.361 0-.722l-.359-.652q-.461-.841.018-1.67t1.436-.849l.744-.016q.413-.008.626-.361l.387-.637q.496-.819 1.454-.819q.957 0 1.453.819z");
}

</style>
