<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4288_thi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-alt-off-fill-sharp" /></template>
<style>
.u4288_thi {
  fill: currentColor;
  d: path("M15.328 14.086L7.471 6.228l1.615-3.634C9.247 2.233 9.605 2 10 2h7a1 1 0 0 1 .868 1.496L14.723 9H18a1.002 1.002 0 0 1 .707 1.707ZM2.707 4.293l17 17a.999.999 0 1 1-1.414 1.414L12.5 16.914l-4.793 4.793a1 1 0 0 1-1.683-.924L7.753 13H6a1 1 0 0 1-.914-1.406l.644-1.449l-4.437-4.438a.999.999 0 1 1 1.414-1.414");
}

</style>
