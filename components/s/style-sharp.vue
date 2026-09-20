<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd03cob-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:style-sharp" /></template>
<style>
.hd03cob-y {
  fill: currentColor;
  d: path("m3.975 19.8l-2.7-1.1l2.7-5.85zm2-5.8l2.875 8H5.975zm5.25 8.6L5.375 6.55l11.35-4.15l5.85 16.05zm.463-12.888q.287-.287.287-.712t-.287-.712T10.975 8t-.712.288T9.975 9t.288.713t.712.287t.713-.288");
}

</style>
