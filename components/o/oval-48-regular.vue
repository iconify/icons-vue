<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gaj4gh-hq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:oval-48-regular" /></template>
<style>
.gaj4gh-hq {
  fill: currentColor;
  d: path("M4 24c0-8.284 6.716-15 15-15h10c8.284 0 15 6.716 15 15s-6.716 15-15 15H19c-8.284 0-15-6.716-15-15m15-12.5c-6.904 0-12.5 5.596-12.5 12.5S12.096 36.5 19 36.5h10c6.904 0 12.5-5.596 12.5-12.5S35.904 11.5 29 11.5z");
}

</style>
