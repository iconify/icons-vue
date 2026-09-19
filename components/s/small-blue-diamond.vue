<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="yvs5yqzlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:small-blue-diamond" /></template>
<style>
.yvs5yqzlt {
  fill: currentColor;
  d: path("m16 32l15.999-16l16 16l-16 16z");
}

</style>
