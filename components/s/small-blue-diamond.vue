<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hcn1bidqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:small-blue-diamond" /></template>
<style>
.hcn1bidqy {
  fill: var(--svg-color--0071b8, #0071b8);
  d: path("m16.019 32l15.98-15.981l15.98 15.98L32 47.98z");
}

</style>
