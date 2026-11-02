<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5g-q6bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-fill-round" /></template>
<style>
.u5g-q6bcn {
  fill: currentColor;
  d: path("M6 3h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m1 3a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-1 7h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m1 3a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
