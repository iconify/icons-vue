<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgoyk0zqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:x-ray-wave" /></template>
<style>
.cgoyk0zqr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.09 8.703q.449-.788 1.137-1.476Q9.204 5.25 12 5.25t4.773 1.977T18.75 12q0 .975-.241 1.851q.325.399.616.399q.73 0 1.673-2.513q.052-.14.154-.249t.238-.171t.285-.067t.288.048q.07.026.132.065q.063.039.117.089t.097.11t.074.128q.03.067.047.139t.02.146q.002.073-.01.146t-.038.142q-1.307 3.487-3.077 3.487q-.638 0-1.215-.453q-.449.788-1.137 1.476Q14.796 18.75 12 18.75t-4.773-1.977T5.25 12q0-.975.241-1.851q-.325-.399-.616-.399q-.73 0-1.673 2.513q-.052.14-.154.249t-.238.171t-.285.067t-.288-.048q-.07-.026-.132-.065q-.063-.039-.117-.089t-.097-.11t-.074-.128q-.03-.067-.047-.139t-.02-.146q-.002-.073.01-.146t.038-.142Q3.105 8.25 4.875 8.25q.638 0 1.215.453");
}

</style>
