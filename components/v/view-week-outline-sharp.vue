<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixul04bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-week-outline-sharp" /></template>
<style>
.ixul04bmd {
  fill: currentColor;
  d: path("M4 18h4V6H4zm6 0h4V6h-4zm6 0h4V6h-4zm6 2H2V4h20z");
}

</style>
