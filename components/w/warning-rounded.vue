<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_qnh9p1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:warning-rounded" /></template>
<style>
.q_qnh9p1s {
  fill: currentColor;
  d: path("M4.126 20q-.234 0-.414-.111t-.28-.293q-.108-.179-.12-.387q-.01-.209.118-.421L11.3 5.212q.128-.212.308-.308T12 4.808t.391.096t.308.308l7.871 13.576q.128.212.115.417t-.118.391t-.282.295t-.41.109zm8.308-2.566q.182-.182.182-.434t-.182-.434t-.434-.181t-.434.181t-.182.434t.182.434t.434.181t.434-.181m-.077-2.193q.143-.144.143-.356v-4q0-.213-.144-.357t-.357-.143t-.356.143t-.143.357v4q0 .212.144.356t.357.144t.356-.144");
}

</style>
