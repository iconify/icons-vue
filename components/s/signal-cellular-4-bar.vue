<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_cyzplpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:signal-cellular-4-bar" /></template>
<style>
.g_cyzplpb {
  fill: currentColor;
  d: path("M2 22h20V2z");
}

</style>
