<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc2312bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:web-asset-outline-sharp" /></template>
<style>
.oc2312bsd {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h16V8H4z");
}

</style>
