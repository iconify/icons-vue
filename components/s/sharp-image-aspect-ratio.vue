<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd1cvpb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-image-aspect-ratio" /></template>
<style>
.xd1cvpb2o {
  fill: currentColor;
  d: path("M16 10h-2v2h2zm0 4h-2v2h2zm-8-4H6v2h2zm4 0h-2v2h2zm10-6H2v16h20zm-2 14H4V6h16z");
}

</style>
