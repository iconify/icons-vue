<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar1tqx03v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-crop" /></template>
<style>
.ar1tqx03v {
  fill: currentColor;
  d: path("M17 15h2V5H9v2h8zM7 17V1H5v4H1v2h4v12h12v4h2v-4h4v-2z");
}

</style>
