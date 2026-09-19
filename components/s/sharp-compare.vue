<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfgvg5b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-compare" /></template>
<style>
.sfgvg5b2w {
  fill: currentColor;
  d: path("M10 3H3v18h7v2h2V1h-2zm0 15H5l5-6zM21 3h-7v2h5v13l-5-6v9h7z");
}

</style>
