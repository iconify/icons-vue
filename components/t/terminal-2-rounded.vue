<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmqx-bw7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:terminal-2-rounded" /></template>
<style>
.dmqx-bw7r {
  fill: currentColor;
  d: path("M13 19q-.213 0-.356-.144t-.144-.357t.144-.356T13 18h6q.213 0 .356.144t.144.357t-.144.356T19 19zm-3.671-9L5.377 6.048q-.146-.146-.146-.347t.146-.347t.35-.146t.358.146l4.08 4.08q.243.243.243.566t-.242.566l-4.081 4.08q-.153.146-.358.146t-.35-.146t-.146-.347t.146-.347z");
}

</style>
