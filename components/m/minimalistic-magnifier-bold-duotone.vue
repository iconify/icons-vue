<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="cl66i7bqg"/><path class="j_45oebel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifier-bold-duotone" /></template>
<style>
.cl66i7bqg {
  cx: 11.5px;
  cy: 11.5px;
  r: 9.5px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.j_45oebel {
  fill: currentColor;
  d: path("M19.4697 19.4697C19.7626 19.1768 20.2373 19.1768 20.5302 19.4697L22.5302 21.4697C22.8231 21.7626 22.8231 22.2374 22.5302 22.5303C22.2373 22.8232 21.7626 22.8232 21.4697 22.5303L19.4697 20.5303C19.1768 20.2374 19.1768 19.7626 19.4697 19.4697Z");
}

</style>
