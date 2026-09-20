<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxpqd354j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nearby-outline-sharp" /></template>
<style>
.sxpqd354j {
  fill: currentColor;
  d: path("M12 16.4L7.6 12L12 7.6l4.4 4.4zm0 6.375L1.225 12L12 1.225L22.775 12zm0-3.575l7.2-7.2L12 4.8L4.8 12z");
}

</style>
