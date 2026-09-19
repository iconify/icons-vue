<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="jaca2pbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:medium-skin-tone" /></template>
<style>
.jaca2pbta {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--d6a57c, #d6a57c);
}

</style>
