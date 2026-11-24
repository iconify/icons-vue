<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vudjtp8wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:university-fill" /></template>
<style>
.vudjtp8wz {
  fill: currentColor;
  d: path("M12.351 9.936a1 1 0 0 1-.702 0l-8-3a1 1 0 0 1 0-1.872l8-3a1 1 0 0 1 .702 0l8 3A1 1 0 0 1 21 6v.014V6v3a1 1 0 0 1-2 0V7.443ZM7 12v5a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0m4 0v5a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0m4 0v5a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0m4 0v5a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0M3 20h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
