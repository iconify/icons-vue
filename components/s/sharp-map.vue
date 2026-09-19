<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0mbrxbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-map" /></template>
<style>
.z0mbrxbfg {
  fill: currentColor;
  d: path("M15 5.1L9 3L3 5.02v16.2l6-2.33l6 2.1l6-2.02V2.77zm0 13.79l-6-2.11V5.11l6 2.11z");
}

</style>
