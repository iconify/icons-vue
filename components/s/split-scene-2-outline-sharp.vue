<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo2mxhbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:split-scene-2-outline-sharp" /></template>
<style>
.mo2mxhbpb {
  fill: currentColor;
  d: path("M4 21v-6h2v4h12v-4h2v6zm-2-8v-2h2V3h16v8h2v2zm4-2h12V5H6zm12 8H6zm0-14H6z");
}

</style>
