<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxrmu3bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-amp-stories" /></template>
<style>
.dxrmu3bmu {
  fill: currentColor;
  d: path("M7 4h10v15H7zM3 6h2v11H3zm16 0h2v11h-2z");
}

</style>
