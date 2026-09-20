<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw73rrvjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-select-move-forward-word" /></template>
<style>
.fw73rrvjs {
  fill: currentColor;
  d: path("m17 16l-1.4-1.4l1.575-1.6H11v-2h6.175L15.6 9.4L17 8l4 4zM3 21V3h6v18zm8 0v-2h2v2zm0-16V3h2v2zm4 16v-2h2v2zm0-16V3h2v2zm4 16v-2h2v2zm0-16V3h2v2z");
}

</style>
