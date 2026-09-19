<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ep3is9lch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:red-triangle-pointed-up" /></template>
<style>
.ep3is9lch {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 2L2 62h60z");
}

</style>
