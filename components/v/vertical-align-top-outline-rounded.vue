<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9cj7obtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vertical-align-top-outline-rounded" /></template>
<style>
.a9cj7obtg {
  fill: currentColor;
  d: path("M5.5 5q-.213 0-.357-.143T5 4.5t.143-.357T5.5 4h13q.214 0 .357.143T19 4.5t-.143.357T18.5 5zm6.143 14.857q-.143-.143-.143-.357V9.608l-2.746 2.746q-.16.16-.354.16t-.354-.16t-.15-.363q.01-.205.15-.345l3.389-3.388q.13-.131.267-.184T12 8.021t.298.053t.268.184l3.388 3.388q.16.16.16.354t-.16.354t-.364.15t-.344-.15L12.5 9.608V19.5q0 .214-.143.357T12 20t-.357-.143");
}

</style>
