<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h6_111r0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:projection-screen-20-regular" /></template>
<style>
.h6_111r0a {
  fill: currentColor;
  d: path("M3 3a1 1 0 0 0 0 2v6a3 3 0 0 0 3 3h3.5v2h-2a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1h-2v-2H14a3 3 0 0 0 3-3V5a1 1 0 1 0 0-2zm1 2h12v6a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2z");
}

</style>
