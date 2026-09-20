<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp19homph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:variables-outline-sharp" /></template>
<style>
.bp19homph {
  fill: currentColor;
  d: path("M4 16V8h16v8zm1-1h14V9H5zm0 0V9z");
}

</style>
