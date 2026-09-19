<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6wy1zbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-mms" /></template>
<style>
.s6wy1zbls {
  fill: currentColor;
  d: path("M22 2H2v20l4-4h16zM5 14l3.5-4.5l2.5 3.01L14.5 8l4.5 6z");
}

</style>
