<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk2wxdb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-alt-bulk-sharp" /></template>
<style>
.fk2wxdb2i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 2a1 1 0 0 1 .868 1.496L14.723 9H18a1.002 1.002 0 0 1 .707 1.707l-11 11a1 1 0 0 1-1.683-.924L7.753 13H6a1 1 0 0 1-.914-1.406l4-9C9.247 2.233 9.605 2 10 2Z");
}

</style>
