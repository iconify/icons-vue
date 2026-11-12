<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoke8092o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-arrow-left-fill-round" /></template>
<style>
.eoke8092o {
  fill: currentColor;
  d: path("M2 6c0-1.064.418-2.078 1.172-2.828A3.98 3.98 0 0 1 6 2a1 1 0 0 1 0 2c-.533 0-1.039.207-1.414.586A1.98 1.98 0 0 0 4 6a1 1 0 0 1-2 0m8-4h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2m8 0c1.064 0 2.078.418 2.828 1.172A3.98 3.98 0 0 1 22 6a1 1 0 0 1-2 0c0-.533-.207-1.039-.586-1.414A1.98 1.98 0 0 0 18 4a1 1 0 0 1 0-2m-6.293 7.707L10.414 11H16a1 1 0 0 1 0 2h-5.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a.997.997 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414M2 14v-4a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0m20 0a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0ZM6 22a3.98 3.98 0 0 1-2.828-1.172A3.98 3.98 0 0 1 2 18a1 1 0 0 1 2 0c0 .533.207 1.039.586 1.414c.377.377.881.588 1.414.586a1 1 0 0 1 0 2m16-4a3.98 3.98 0 0 1-1.172 2.828A3.98 3.98 0 0 1 18 22a1 1 0 0 1 0-2c.533 0 1.039-.207 1.414-.586c.377-.377.588-.881.586-1.414a1 1 0 0 1 2 0m-12 4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2Z");
}

</style>
