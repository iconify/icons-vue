<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqokxpsvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:upcoming-rounded" /></template>
<style>
.rqokxpsvz {
  fill: currentColor;
  d: path("M4.616 20q-.672 0-1.144-.472T3 18.385v-3.77q0-.67.472-1.143Q3.944 13 4.616 13h2.957q.26 0 .458.154t.286.388q.433 1.1 1.452 1.78Q10.79 16 12 16q1.23 0 2.25-.679t1.433-1.779q.088-.234.296-.388t.467-.154h2.938q.672 0 1.144.472T21 14.616v3.769q0 .67-.472 1.143q-.472.472-1.143.472zm12.438-9.67q-.16-.159-.16-.353t.16-.354l2.15-2.15q.14-.14.344-.15t.364.15t.16.354t-.16.354l-2.15 2.15q-.14.14-.345.15t-.363-.15m-10.108 0q-.16.16-.354.16t-.354-.16l-2.15-2.15q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16l2.15 2.15q.14.14.15.344t-.15.364m4.697-2.436q-.143-.143-.143-.356v-3q0-.214.143-.357T12 4.039t.357.143t.143.357v3q0 .213-.143.356T12 8.04t-.357-.144");
}

</style>
