<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hllc59b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-bookmark" /></template>
<style>
.hllc59b3d {
  fill: currentColor;
  d: path("M19 3H5v18l7-3l7 3z");
}

</style>
