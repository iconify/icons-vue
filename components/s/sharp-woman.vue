<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo10z7n7k"/><circle class="yfz3w9lrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-woman" /></template>
<style>
.yfz3w9lrl {
  cx: 12px;
  cy: 4px;
  r: 2px;
  fill: currentColor;
}

.zo10z7n7k {
  fill: currentColor;
  d: path("M13.41 7h-2.82L7 16h3v6h4v-6h3z");
}

</style>
