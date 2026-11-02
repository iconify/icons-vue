<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5ou_6b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paint-bucket-fill" /></template>
<style>
.n5ou_6b6w {
  fill: currentColor;
  d: path("m8.707 2.293l9 9a1 1 0 0 1 0 1.414l-7 7a2.414 2.414 0 0 1-3.414 0l-4-4a2.414 2.414 0 0 1 0-3.414L9.586 6L7.293 3.707a.999.999 0 1 1 1.414-1.414M7.414 11h7.172L11 7.414Zm14.35 9.168a3.004 3.004 0 0 1-4.423 1.332A3 3 0 0 1 16 19c0-.774.371-1.494.825-2.1c.436-.581.955-1.095 1.468-1.607a1 1 0 0 1 1.414 0c.513.512 1.032 1.026 1.468 1.607c.454.606.825 1.326.825 2.1c.001.401-.079.799-.236 1.168");
}

</style>
