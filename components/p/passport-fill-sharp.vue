<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg-w2ibtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:passport-fill-sharp" /></template>
<style>
.sg-w2ibtw {
  fill: currentColor;
  d: path("M4 3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Zm4 7a4 4 0 1 0 8 0a4 4 0 0 0-8 0m7 6H9a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2");
}

</style>
