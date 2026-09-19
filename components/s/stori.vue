<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ji02gx97v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stori" /></template>
<style>
.ji02gx97v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37 15.5v-9a2 2 0 0 0-2-2h-9a2 2 0 0 0-2 2V9a2 2 0 0 1-2 2h-9a2 2 0 0 0-2 2v9a2 2 0 0 0 2 2h11v-4.5a2 2 0 0 1 2-2h9a2 2 0 0 0 2-2m-26 17v9a2 2 0 0 0 2 2h9a2 2 0 0 0 2-2V39a2 2 0 0 1 2-2h9a2 2 0 0 0 2-2v-9a2 2 0 0 0-2-2H24v4.5a2 2 0 0 1-2 2h-9a2 2 0 0 0-2 2");
}

</style>
