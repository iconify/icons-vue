<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mstwh7jxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-compare-outline-sharp" /></template>
<style>
.mstwh7jxr {
  fill: currentColor;
  d: path("M11 22.23V20H4V4h7V1.77h1v20.46zM5 19h6v-3H7.5v-1H11v-2.5H7.5v-1H11V9H7.5V8H11V5H5zm9.192-14V4h6v16h-6v-1h5V5zm0 7.5v-1h3.5v1zm0-3.5V8h3.5v1zM11 12");
}

</style>
