<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr4c4xbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:maximize-outline-sharp" /></template>
<style>
.wr4c4xbqx {
  fill: currentColor;
  d: path("M4 5V3h16v2z");
}

</style>
