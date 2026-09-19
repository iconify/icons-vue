<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="x2xu2umfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:minus-sign" /></template>
<style>
.x2xu2umfc {
  fill: currentColor;
  d: path("M2 26h60v12H2z");
}

</style>
