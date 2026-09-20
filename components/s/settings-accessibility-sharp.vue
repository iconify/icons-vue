<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgy2zqb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-accessibility-sharp" /></template>
<style>
.zgy2zqb5u {
  fill: currentColor;
  d: path("M10.799 3.316q-.491-.491-.491-1.2q0-.71.491-1.201Q11.291.423 12 .423t1.201.492q.491.49.491 1.2t-.491 1.201q-.492.492-1.201.492t-1.201-.492m-.991 15.569V6.423q-1.558-.125-3.031-.346T4 5.539l.23-1q1.893.467 3.814.676q1.921.208 3.956.208t3.956-.208q1.921-.21 3.813-.676l.231 1q-1.304.317-2.777.538t-3.03.346v12.462h-1v-6.039h-2.385v6.039zM7.46 23.54q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m4 0q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m4 0q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23");
}

</style>
