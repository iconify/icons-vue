<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rdyvtebzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:small-blue-diamond" /></template>
<style>
.rdyvtebzo {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M7.707 18.708a1.003 1.003 0 0 1 0-1.414l9.585-9.586a1.003 1.003 0 0 1 1.414 0l9.587 9.587a1.003 1.003 0 0 1 0 1.414l-9.587 9.585a1.003 1.003 0 0 1-1.414 0z");
}

</style>
