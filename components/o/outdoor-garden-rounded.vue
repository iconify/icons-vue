<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fced2hbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:outdoor-garden-rounded" /></template>
<style>
.fced2hbbk {
  fill: currentColor;
  d: path("M2 21h6V6L5 3L2 6zm7 0h6V6l-3-3l-3 3zm7 0h6V6l-3-3l-3 3z");
}

</style>
