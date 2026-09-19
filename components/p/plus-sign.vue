<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="m_-w-djsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:plus-sign" /></template>
<style>
.m_-w-djsn {
  fill: currentColor;
  d: path("M38 26V2H26v24H2v12h24v24h12V38h24V26z");
}

</style>
