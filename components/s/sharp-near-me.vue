<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umy8kdbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-near-me" /></template>
<style>
.umy8kdbsc {
  fill: currentColor;
  d: path("M21 3L3 10.53v.98l6.84 2.65L12.48 21h.98z");
}

</style>
