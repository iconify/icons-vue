<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-so5mk4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:manga-outline-sharp" /></template>
<style>
.i-so5mk4z {
  fill: currentColor;
  d: path("M3 19V5h18v14zm5.735-1L7.64 16.5l1.783-2.46v-3.046l2.886-.937l1.807-2.46L17 8.518l3-.975V6H4v12zm1.225 0h9.425q.23 0 .423-.192t.192-.424V9.43l-.483-.675L17 9.58l-2.492-.827l-1.568 2.142l-2.515.813v2.643L8.865 16.5z");
}

</style>
