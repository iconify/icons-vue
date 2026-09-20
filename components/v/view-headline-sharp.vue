<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xevf-bbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-headline-sharp" /></template>
<style>
.xevf-bbet {
  fill: currentColor;
  d: path("M4.5 14.385v-1h15v1zm0 3.769v-1h15v1zm0-7.538v-1h15v1zm0-3.77v-1h15v1z");
}

</style>
