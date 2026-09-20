<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="goajxdqhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:thumbnail-bar-sharp" /></template>
<style>
.goajxdqhb {
  fill: currentColor;
  d: path("M2 20V4h6v16zm8 0V4h12v16z");
}

</style>
