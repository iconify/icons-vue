<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt4e-oebs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-4-bar-outline" /></template>
<style>
.jt4e-oebs {
  fill: currentColor;
  d: path("M2 22L22 2v20z");
}

</style>
