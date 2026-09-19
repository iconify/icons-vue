<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dshc49bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-filter-hdr" /></template>
<style>
.dshc49bdi {
  fill: currentColor;
  d: path("m14 6l-4.22 5.63l1.25 1.67L14 9.33L19 16h-8.46l-4.01-5.37L1 18h22zM5 16l1.52-2.03L8.04 16z");
}

</style>
