<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8ui6_1fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:temperature-celsius-fill-sharp" /></template>
<style>
.r8ui6_1fu {
  fill: currentColor;
  d: path("M2 7a3 3 0 1 1 6 0a3 3 0 0 1-6 0m16-1h-2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2a1 1 0 0 1 2 0a3.98 3.98 0 0 1-1.172 2.828A3.98 3.98 0 0 1 18 20h-2a4 4 0 0 1-4-4V8a4 4 0 0 1 4-4h2c1.064 0 2.078.418 2.828 1.172A3.98 3.98 0 0 1 22 8a1 1 0 0 1-2 0a2 2 0 0 0-2-2M4 7a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
