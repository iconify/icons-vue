<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujoxd3bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-off-fill" /></template>
<style>
.ujoxd3bia {
  fill: currentColor;
  d: path("m3.707 1.293l19 19a.999.999 0 1 1-1.414 1.414l-3.494-3.493c-1.502 1.609-3.39 2.809-5.393 3.7a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V5c0-.448.099-.889.292-1.293l-.999-1a.999.999 0 1 1 1.414-1.414m16.34 13.512L7.243 2H18a3 3 0 0 1 3 3v5c0 1.645-.302 3.291-.953 4.805");
}

</style>
