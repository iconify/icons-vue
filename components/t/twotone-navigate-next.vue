<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_eprobji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-navigate-next" /></template>
<style>
.p_eprobji {
  fill: currentColor;
  d: path("m10.02 18l6-6l-6-6l-1.41 1.41L13.19 12l-4.58 4.59z");
}

</style>
