<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axd17qbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mode-comment-sharp" /></template>
<style>
.axd17qbjc {
  fill: currentColor;
  d: path("M2 18V2h20v20l-4-4z");
}

</style>
