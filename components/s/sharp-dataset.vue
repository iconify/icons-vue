<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oio230l4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-dataset" /></template>
<style>
.oio230l4t {
  fill: currentColor;
  d: path("M21 3H3v18h18zM11 17H7v-4h4zm0-6H7V7h4zm6 6h-4v-4h4zm0-6h-4V7h4z");
}

</style>
