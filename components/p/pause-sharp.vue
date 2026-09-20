<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itwjg14iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pause-sharp" /></template>
<style>
.itwjg14iq {
  fill: currentColor;
  d: path("M14 19V5h4v14zm-8 0V5h4v14z");
}

</style>
