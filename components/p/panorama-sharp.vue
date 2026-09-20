<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz9bpmbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:panorama-sharp" /></template>
<style>
.wz9bpmbgi {
  fill: currentColor;
  d: path("M3 19V5h18v14zm4.5-3h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115z");
}

</style>
