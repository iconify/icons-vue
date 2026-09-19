<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zphq_iblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-straighten" /></template>
<style>
.zphq_iblu {
  fill: currentColor;
  d: path("M23 6H1v12h22zm-2 10H3V8h2v4h2V8h2v4h2V8h2v4h2V8h2v4h2V8h2z");
}

</style>
