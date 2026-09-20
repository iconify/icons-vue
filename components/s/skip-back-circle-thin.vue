<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pbi6flbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:skip-back-circle-thin" /></template>
<style>
.pbi6flbqx {
  fill: currentColor;
  d: path("M128 28a100 100 0 1 0 100 100A100.11 100.11 0 0 0 128 28m0 192a92 92 0 1 1 92-92a92.1 92.1 0 0 1-92 92m33.94-135.5a4 4 0 0 0-4.06.11L100 120.78V88a4 4 0 0 0-8 0v80a4 4 0 0 0 8 0v-32.78l57.88 36.17a4 4 0 0 0 2.12.61a4.06 4.06 0 0 0 1.94-.5A4 4 0 0 0 164 168V88a4 4 0 0 0-2.06-3.5M156 160.78L103.55 128L156 95.22Z");
}

</style>
