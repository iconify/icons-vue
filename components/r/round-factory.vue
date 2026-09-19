<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk_a2-bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-factory" /></template>
<style>
.bk_a2-bbt {
  fill: currentColor;
  d: path("M14 10V8.48c0-.71-.71-1.19-1.37-.93L9 9v-.48c0-.72-.73-1.21-1.39-.92l-4.4 1.88C2.48 9.8 2 10.52 2 11.32V20c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V10zm-5 7c0 .55-.45 1-1 1s-1-.45-1-1v-2c0-.55.45-1 1-1s1 .45 1 1zm4 0c0 .55-.45 1-1 1s-1-.45-1-1v-2c0-.55.45-1 1-1s1 .45 1 1zm4 0c0 .55-.45 1-1 1s-1-.45-1-1v-2c0-.55.45-1 1-1s1 .45 1 1zm3.12-15h-1.23c-.51 0-.93.38-.99.88l-.7 5.62h4.6l-.69-5.62c-.06-.5-.49-.88-.99-.88");
}

</style>
