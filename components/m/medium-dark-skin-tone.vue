<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="cytjfwb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:medium-dark-skin-tone" /></template>
<style>
.cytjfwb1u {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--b47d56, #b47d56);
}

</style>
