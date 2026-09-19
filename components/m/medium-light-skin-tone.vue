<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="s-t8usfrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:medium-light-skin-tone" /></template>
<style>
.s-t8usfrs {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--fed0ac, #fed0ac);
}

</style>
