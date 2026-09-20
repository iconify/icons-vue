<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehl285bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:upload-file-sharp" /></template>
<style>
.ehl285bxr {
  fill: currentColor;
  d: path("M11.5 17.77h1v-4.695l2.1 2.1l.708-.713L12 11.154l-3.308 3.308l.714.707l2.094-2.094zM5 21V3h9.5L19 7.5V21zm9-13h4l-4-4z");
}

</style>
