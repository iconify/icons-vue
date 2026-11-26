<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf-cs3dxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:underwear-sharp-fill" /></template>
<style>
.uf-cs3dxm {
  fill: currentColor;
  d: path("M12 4L22 4C22.5523 4 23 4.4477 23 5L23 10C23 10.4304 22.7246 10.8126 22.3162 10.9487L16.8167 12.7819L14.9615 19.2747C14.8389 19.704 14.4465 20 14 20L10 20C9.5535 20 9.1611 19.704 9.0385 19.2747L7.1833 12.7819L1.6838 10.9487C1.2754 10.8126 1 10.4304 1 10L1 5C1 4.4477 1.4477 4 2 4Z");
}

</style>
