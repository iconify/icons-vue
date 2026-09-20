<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="d4h73_bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:square-split-horizontal-thin" /></template>
<style>
.d4h73_bxi {
  fill: currentColor;
  d: path("M200 44H56a12 12 0 0 0-12 12v144a12 12 0 0 0 12 12h144a12 12 0 0 0 12-12V56a12 12 0 0 0-12-12M52 200V56a4 4 0 0 1 4-4h68v152H56a4 4 0 0 1-4-4m152 0a4 4 0 0 1-4 4h-68V52h68a4 4 0 0 1 4 4Z");
}

</style>
