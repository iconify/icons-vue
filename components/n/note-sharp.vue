<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_u9enura"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:note-sharp" /></template>
<style>
.d_u9enura {
  fill: currentColor;
  d: path("M5 21V3h9.5L19 7.5V21zm9-13h4l-4-4z");
}

</style>
