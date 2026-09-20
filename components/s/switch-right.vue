<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt6xfzbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-right" /></template>
<style>
.xt6xfzbhn {
  fill: currentColor;
  d: path("M10 17.48L4.52 12L10 6.52zm4 0V6.52L19.48 12zm.885-2.124L18.24 12l-3.356-3.356z");
}

</style>
