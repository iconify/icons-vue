<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbr38ov7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trip-sharp" /></template>
<style>
.jbr38ov7b {
  fill: currentColor;
  d: path("M17 20V7h4v13zM10 7h4V5h-4zM8 20V7h1V4h6v3h1v13zm-5 0V7h4v13z");
}

</style>
