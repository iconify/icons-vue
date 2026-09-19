<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv-ngwpls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-print" /></template>
<style>
.wv-ngwpls {
  fill: currentColor;
  d: path("M22 8H2v9h4v4h12v-4h4zm-6 11H8v-5h8zm3-7c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m-1-9H6v4h12z");
}

</style>
