<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="djo91-bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-away-12-filled" /></template>
<style>
.djo91-bxx {
  fill: currentColor;
  d: path("M6 12A6 6 0 1 0 6 0a6 6 0 0 0 0 12m.5-8.75v2.405l1.488 1.276a.75.75 0 1 1-.976 1.138l-1.75-1.5A.75.75 0 0 1 5 6V3.25a.75.75 0 0 1 1.5 0");
}

</style>
