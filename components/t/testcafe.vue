<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":164};
const content = `<path class="ot66lkavl"/><path class="owtg22ymp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:testcafe" /></template>
<style>
.ot66lkavl {
  fill: var(--svg-color--404142, #404142);
  d: path("m158.898 109.302l-8.826 9.107h35.312l35.311 31.882H35.312l35.311-31.882h26.485l-8.839-9.107H61.797L0 163.954h256l-61.79-54.652z");
}

.owtg22ymp {
  fill: var(--svg-color--37b5e5, #37b5e5);
  d: path("M237.425 22.079L215.462 0l-92.223 92.757l-35.128-35.339l-21.956 22.086l57.09 57.418l114.18-114.836z");
}

</style>
