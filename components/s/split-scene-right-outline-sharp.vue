<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9dz09yvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:split-scene-right-outline-sharp" /></template>
<style>
.u9dz09yvh {
  fill: currentColor;
  d: path("M3 20V4h6v2H5v12h4v2zm8 2V2h2v2h8v16h-8v2zm-6-4V6z");
}

</style>
