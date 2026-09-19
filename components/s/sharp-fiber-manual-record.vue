<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="rnr15yq7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-fiber-manual-record" /></template>
<style>
.rnr15yq7m {
  cx: 12px;
  cy: 12px;
  r: 8px;
  fill: currentColor;
}

</style>
