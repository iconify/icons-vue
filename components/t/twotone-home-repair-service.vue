<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbd4uwbhb"/><path class="janqnhb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-home-repair-service" /></template>
<style>
.gbd4uwbhb {
  fill: currentColor;
  d: path("M20 8h-3V6c0-1.1-.9-2-2-2H9c-1.1 0-2 .9-2 2v2H4c-1.1 0-2 .9-2 2v10h20V10c0-1.1-.9-2-2-2M9 6h6v2H9zm11 12H4v-3h2v1h2v-1h8v1h2v-1h2zm0-5h-2v-1h-2v1H8v-1H6v1H4v-3h16z");
}

.janqnhb1v {
  fill: currentColor;
  d: path("M18 16h-2v-1H8v1H6v-1H4v3h16v-3h-2zM4 10v3h2v-1h2v1h8v-1h2v1h2v-3H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
