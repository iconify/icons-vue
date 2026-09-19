<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="yvb0blvjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:red-circle" /></template>
<style>
.yvb0blvjs {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ed4c5c, #ed4c5c);
}

</style>
