<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xla7kib8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-alt-2-bar-outline-sharp" /></template>
<style>
.xla7kib8f {
  fill: currentColor;
  d: path("M5 20v-6h3v6zm6 0V9h3v11z");
}

</style>
