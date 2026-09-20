<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h94z2xbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trackpad-input-2-rounded" /></template>
<style>
.h94z2xbmf {
  fill: currentColor;
  d: path("M17.885 14.327v-2.385q0-.213.143-.356q.143-.144.357-.144q.213 0 .356.144t.144.356v2.385h1.769q0-.213.143-.357q.143-.143.357-.143q.213 0 .356.143t.144.357V17.5q0 1.458-1.021 2.479T18.153 21h-3.482q-.504 0-.948-.186t-.812-.554l-3.803-3.79q-.217-.218-.22-.544t.214-.568l.034-.035q.235-.235.543-.292q.307-.058.634.028l2.033.462V8.52q0-.213.143-.357t.357-.143t.357.143q.143.144.143.357v5.808h1.77V7.25q0-.213.143-.357t.357-.143t.356.143q.144.144.144.357v7.077zM4.615 18q-.69 0-1.152-.462T3 16.384V5.616q0-.691.463-1.153T4.615 4h13.77q.69 0 1.152.463T20 5.616v2.942q0 .213-.143.357t-.357.143t-.357-.143T19 8.558V5.616q0-.231-.192-.424T18.384 5H4.616q-.231 0-.424.192T4 5.616v10.769q0 .23.192.423t.423.192h1.8q.214 0 .357.143q.144.144.144.357t-.144.357t-.357.143z");
}

</style>
