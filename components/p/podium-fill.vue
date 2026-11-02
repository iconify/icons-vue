<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si2clubvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:podium-fill" /></template>
<style>
.si2clubvz {
  fill: currentColor;
  d: path("M7 11V7a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v7h2a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-5a3 3 0 0 1 3-3Zm3.293-.707a.999.999 0 1 0 1.414 1.414l.293-.293V15a1 1 0 0 0 2 0V9a1.002 1.002 0 0 0-1.707-.707ZM7 13H5a.997.997 0 0 0-1 1v5a1 1 0 0 0 1 1h2Zm10 7h2a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1h-2Z");
}

</style>
