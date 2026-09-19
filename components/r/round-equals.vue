<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlxuxlbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-equals" /></template>
<style>
.wlxuxlbuw {
  fill: currentColor;
  d: path("M18 9.998H6a1 1 0 1 1 0-2h12a1 1 0 0 1 0 2m0 6H6a1 1 0 0 1 0-2h12a1 1 0 0 1 0 2");
}

</style>
