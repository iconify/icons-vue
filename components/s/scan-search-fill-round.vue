<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6pn90bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-search-fill-round" /></template>
<style>
.q6pn90bky {
  fill: currentColor;
  d: path("M2 7c0-1.33.522-2.597 1.464-3.536A5 5 0 0 1 7 2a1 1 0 0 1 0 2a2.98 2.98 0 0 0-2.121.879A2.98 2.98 0 0 0 4 7a1 1 0 0 1-2 0m14-4a1 1 0 0 1 1-1a5 5 0 0 1 3.536 1.464A4.98 4.98 0 0 1 22 7a1 1 0 0 1-2 0c0-.799-.312-1.558-.879-2.121A2.98 2.98 0 0 0 17 4a1 1 0 0 1-1-1m-.653 10.933l2.36 2.36a.999.999 0 1 1-1.414 1.414l-2.36-2.36a5.244 5.244 0 1 1 1.414-1.414M5.053 21.607a5 5 0 0 1-1.589-1.071A5 5 0 0 1 2 17a1 1 0 0 1 2 0a2.98 2.98 0 0 0 .879 2.121A2.98 2.98 0 0 0 7 20a1 1 0 0 1 0 2a5 5 0 0 1-1.947-.393m16.554-2.66a5 5 0 0 1-1.071 1.589A5 5 0 0 1 17 22a1 1 0 0 1 0-2a2.98 2.98 0 0 0 2.121-.879A2.98 2.98 0 0 0 20 17a1 1 0 0 1 2 0a5 5 0 0 1-.393 1.947");
}

</style>
