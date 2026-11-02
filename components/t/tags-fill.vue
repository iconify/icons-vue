<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk96dwbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tags-fill" /></template>
<style>
.zk96dwbth {
  fill: currentColor;
  d: path("M8 5c1.039 0 1.992.578 2.707 1.293l4 4a2.414 2.414 0 0 1 0 3.414l-4 4a2.414 2.414 0 0 1-3.414 0l-4-4C2.578 12.992 2 12.039 2 11V8a3 3 0 0 1 3-3Zm7.707.293l5 5a2.414 2.414 0 0 1 0 3.414l-5 5a.999.999 0 1 1-1.414-1.414l5-5a.414.414 0 0 0 0-.586l-5-5a.999.999 0 1 1 1.414-1.414M7 9a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
