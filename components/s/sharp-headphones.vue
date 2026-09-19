<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_v4i_qaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-headphones" /></template>
<style>
.y_v4i_qaj {
  fill: currentColor;
  d: path("M12 3a9 9 0 0 0-9 9v9h6v-8H5v-1c0-3.87 3.13-7 7-7s7 3.13 7 7v1h-4v8h6v-9a9 9 0 0 0-9-9");
}

</style>
