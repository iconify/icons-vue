<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbt7powrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-crop-portrait" /></template>
<style>
.zbt7powrw {
  fill: currentColor;
  d: path("M19 3H5v18h14zm-2 16H7V5h10z");
}

</style>
