<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj8u7ha2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:museum" /></template>
<style>
.wj8u7ha2l {
  fill: currentColor;
  d: path("M2 22v-2h2v-9H2V9l10-7l10 7v2h-2v9h2v2zm6-4h2v-4l2 3l2-3v4h2v-7h-2l-2 3l-2-3H8z");
}

</style>
