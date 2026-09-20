<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq7nfwa1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trackpad-input-3-sharp" /></template>
<style>
.mq7nfwa1v {
  fill: currentColor;
  d: path("M13.575 22L7.6 16l1.6-1.65l2.8.825V7h2v7h1V6h2v8h1V8h2v6h1v-1h2v5q0 1.65-1.175 2.825T19 22zM2 19V3h19v2H4v12h1.8l1.975 2z");
}

</style>
