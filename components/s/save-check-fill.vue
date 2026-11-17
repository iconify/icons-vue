<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f34g38btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:save-check-fill" /></template>
<style>
.f34g38btk {
  fill: currentColor;
  d: path("M18 22v-6a3 3 0 0 0-3-3H9a3 3 0 0 0-3 3v6H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h11c1.039 0 1.992.578 2.707 1.293l2 2C21.422 6.008 22 6.961 22 8v11a3 3 0 0 1-3 3ZM11 9.586L9.707 8.293a.999.999 0 1 0-1.414 1.414l2 2a1 1 0 0 0 1.414 0l4-4a.999.999 0 1 0-1.414-1.414ZM8 22v-6a.997.997 0 0 1 1-1h6a.997.997 0 0 1 1 1v6Z");
}

</style>
