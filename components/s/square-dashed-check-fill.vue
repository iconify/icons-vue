<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gto--hbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-check-fill" /></template>
<style>
.gto--hbch {
  fill: currentColor;
  d: path("M2 6V5a3 3 0 0 1 3-3h1a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v1a1 1 0 0 1-2 0m8-4h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2m8 0h1a3 3 0 0 1 3 3v1a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-1a1 1 0 0 1 0-2m-9.293 9.293l2.226 2.226l4.299-5.159a1 1 0 1 1 1.536 1.28l-5 6a1 1 0 0 1-1.475.067l-3-3a.999.999 0 1 1 1.414-1.414M2 14v-4a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0m20-4v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0M6 22H5a3 3 0 0 1-3-3v-1a1 1 0 0 1 2 0v1a1 1 0 0 0 1 1h1a1 1 0 0 1 0 2m16-4v1a3 3 0 0 1-3 3h-1a1 1 0 0 1 0-2h1a1 1 0 0 0 1-1v-1a1 1 0 0 1 2 0m-8 4h-4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2");
}

</style>
