<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b2c_aoiqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tablet-phone-desktop-20-regular" /></template>
<style>
.b2c_aoiqm {
  fill: currentColor;
  d: path("M13 3a2 2 0 0 1 2 2v2h1.5A1.5 1.5 0 0 1 18 8.5v6a1.5 1.5 0 0 1-1.5 1.5H14v1h.5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1h.5v-1H8a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-3a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2zm-2 14h2v-1h-2zm-6-1h2v-4H5zm2.5-8a.5.5 0 0 0-.5.5V11a1 1 0 0 1 1 1v3h8.5a.5.5 0 0 0 .5-.5v-6a.5.5 0 0 0-.5-.5zM4 4a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1a1 1 0 0 1 1-1h1V8.5A1.5 1.5 0 0 1 7.5 7H14V5a1 1 0 0 0-1-1z");
}

</style>
