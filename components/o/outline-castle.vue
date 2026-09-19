<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p--uezdat"/><path class="yhps9mbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-castle" /></template>
<style>
.p--uezdat {
  fill: currentColor;
  d: path("M21 9v2h-2V3h-2v2h-2V3h-2v2h-2V3H9v2H7V3H5v8H3V9H1v12h9v-3c0-1.1.9-2 2-2s2 .9 2 2v3h9V9zm0 10h-5v-1c0-2.21-1.79-4-4-4s-4 1.79-4 4v1H3v-6h4V7h10v6h4z");
}

.yhps9mbiv {
  fill: currentColor;
  d: path("M9 9h2v3H9zm4 0h2v3h-2z");
}

</style>
