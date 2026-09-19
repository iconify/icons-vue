<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgtloob5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-wysiwyg" /></template>
<style>
.wgtloob5t {
  fill: currentColor;
  d: path("M17 12H7v-2h10zm-4 2H7v2h6zm8 7H3V3h18zM19 7H5v12h14z");
}

</style>
