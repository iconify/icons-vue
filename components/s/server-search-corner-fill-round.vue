<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if6f1fbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-search-corner-fill-round" /></template>
<style>
.if6f1fbon {
  fill: currentColor;
  d: path("M6 3h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m1.01 3H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m13.283 15.707l-2.386-2.386a3.83 3.83 0 1 1 1.414-1.414l2.386 2.386a.999.999 0 1 1-1.414 1.414M9 21H6a4 4 0 0 1 0-8h3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1m8.695-4.311a1.83 1.83 0 1 0-3.39-1.376a1.83 1.83 0 0 0 3.39 1.376M7.01 16H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
