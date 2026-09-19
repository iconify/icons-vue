<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dw34xcs_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:no-entry" /></template>
<style>
.dw34xcs_l {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32c-.001 16.568 13.432 30 30 30s30.001-13.432 30-30c.001-16.568-13.432-30-30-30M9 38V26h46v12z");
}

</style>
