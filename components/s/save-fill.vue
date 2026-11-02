<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0oa8ejev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:save-fill" /></template>
<style>
.w0oa8ejev {
  fill: currentColor;
  d: path("M18 22v-6a3 3 0 0 0-3-3H9a3 3 0 0 0-3 3v6H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h11c1.039 0 1.992.578 2.707 1.293l2 2C21.422 6.008 22 6.961 22 8v11a3 3 0 0 1-3 3ZM15 6H9a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2M8 22v-6a.997.997 0 0 1 1-1h6a.997.997 0 0 1 1 1v6Z");
}

</style>
