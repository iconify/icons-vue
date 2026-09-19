<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xszgbmujs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:white-large-square" /></template>
<style>
.xszgbmujs {
  fill: currentColor;
  d: path("M60 4v56H4V4zm2-2H2v60h60z");
}

</style>
