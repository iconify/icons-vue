<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ifqwgccfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ticketnunc" /></template>
<style>
.ifqwgccfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.697 28.582H24.65v13.744H6.697zm22.286-.137h12.32V42.5h-12.32zM7.742 5.5h12.474m-6.237 19.19V5.5m12.453 19.303V5.613l12.713 19.19V5.613");
}

</style>
