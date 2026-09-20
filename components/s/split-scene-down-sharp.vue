<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1g2yxbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:split-scene-down-sharp" /></template>
<style>
.p1g2yxbvr {
  fill: currentColor;
  d: path("M4 9V3h16v6zm0 12v-8H2v-2h20v2h-2v8z");
}

</style>
