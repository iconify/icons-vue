<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4z-047ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-first-line-24-filled" /></template>
<style>
.b4z-047ux {
  fill: currentColor;
  d: path("M3.707 3.293a1 1 0 0 0-1.414 1.414L3.586 6L2.293 7.293a1 1 0 0 0 1.414 1.414l2-2a1 1 0 0 0 0-1.414zM10 5a1 1 0 0 0 0 2h11a1 1 0 1 0 0-2zm11 12H3a1 1 0 1 0 0 2h18a1 1 0 1 0 0-2M2 12a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1");
}

</style>
