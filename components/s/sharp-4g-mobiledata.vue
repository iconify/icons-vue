<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwn9s_wmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-4g-mobiledata" /></template>
<style>
.qwn9s_wmz {
  fill: currentColor;
  d: path("M9 7H7v5H5V7H3v7h4v3h2v-3h2v-2H9zm8 4v2h2v2h-5V9h7V7h-9v10h9v-6z");
}

</style>
