<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykwu1pbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pentagon-sharp" /></template>
<style>
.ykwu1pbea {
  fill: currentColor;
  d: path("M6 21L2 9l10-7l10 7l-4 12z");
}

</style>
