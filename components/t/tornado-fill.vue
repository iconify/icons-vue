<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzkuasbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tornado-fill" /></template>
<style>
.mzkuasbkk {
  fill: currentColor;
  d: path("M3 3h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m3 4h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2m3 4h10a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m1 4h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2m1 4a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Z");
}

</style>
