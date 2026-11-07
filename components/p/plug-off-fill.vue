<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcm51ecww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-off-fill" /></template>
<style>
.vcm51ecww {
  fill: currentColor;
  d: path("m20.707 2.707l-18 18a.999.999 0 1 1-1.414-1.414l3.755-3.755A3 3 0 0 1 5 15V9a3 3 0 0 1 3-3V3a1 1 0 0 1 2 0v3h4V3a1 1 0 0 1 2 0v1.586l3.293-3.293a.999.999 0 1 1 1.414 1.414M8.243 18L18.65 7.593c.23.433.35.917.35 1.407v6a3 3 0 0 1-3 3h-3v3a1 1 0 0 1-2 0v-3Z");
}

</style>
