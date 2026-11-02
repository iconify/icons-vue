<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ispjzdbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sim-card-fill" /></template>
<style>
.ispjzdbme {
  fill: currentColor;
  d: path("M4 19V5a3 3 0 0 1 3-3h7c1.039 0 1.992.578 2.707 1.293l2 2C19.422 6.008 20 6.961 20 8v11a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3m5 1h6a3 3 0 0 0 3-3V9a3 3 0 0 0-3-3H9a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3M8 10a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2Zm2 2h4v-2h-4Zm4 4v-2h-4v2Z");
}

</style>
