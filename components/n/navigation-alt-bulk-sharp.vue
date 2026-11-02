<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_wd2dk3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:navigation-alt-bulk-sharp" /></template>
<style>
.v_wd2dk3n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m15.949 11.684l3 9a.999.999 0 0 1-1.396 1.21L12 19.118l-5.553 2.776a.999.999 0 0 1-1.396-1.21l6-18a1 1 0 0 1 1.898 0Z");
}

</style>
