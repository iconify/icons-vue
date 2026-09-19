<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggzzanqbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-local-parking" /></template>
<style>
.ggzzanqbi {
  fill: currentColor;
  d: path("M13 3H6v18h4v-6h3c3.31 0 6-2.69 6-6s-2.69-6-6-6m.2 8H10V7h3.2c1.1 0 2 .9 2 2s-.9 2-2 2");
}

</style>
