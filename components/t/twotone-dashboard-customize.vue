<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvpzxdbes"/><path class="fcvj9i1th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-dashboard-customize" /></template>
<style>
.fcvj9i1th {
  fill: currentColor;
  d: path("M3 11h8V3H3zm2-6h4v4H5zm8-2v8h8V3zm6 6h-4V5h4zM3 21h8v-8H3zm2-6h4v4H5zm13-2h-2v3h-3v2h3v3h2v-3h3v-2h-3z");
}

.gvpzxdbes {
  fill: currentColor;
  d: path("M5 15h4v4H5zM5 5h4v4H5zm10 0h4v4h-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
