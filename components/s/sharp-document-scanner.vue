<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfzufdbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-document-scanner" /></template>
<style>
.kfzufdbnh {
  fill: currentColor;
  d: path("M7 3H4v3H2V1h5zm15 3V1h-5v2h3v3zM7 21H4v-3H2v5h5zm13-3v3h-3v2h5v-5zM19 4v16H5V4zm-4 4H9v2h6zm0 3H9v2h6zm0 3H9v2h6z");
}

</style>
