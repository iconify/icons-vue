<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww26p_aqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-header-4-24-filled" /></template>
<style>
.ww26p_aqi {
  fill: currentColor;
  d: path("M11 5a1 1 0 0 1 1 1v12a1 1 0 1 1-2 0v-5H4v5a1 1 0 1 1-2 0V6a1 1 0 0 1 2 0v5h6V6a1 1 0 0 1 1-1m7.8.444c.731-.877 2.205-.374 2.206.808V14H22l.102.005a1 1 0 0 1 0 1.99L22 16h-.995v2a1 1 0 0 1-2 0v-2h-4.741c-1.215 0-1.926-1.368-1.228-2.362l5.695-8.105zM15.228 14h3.779V8.623z");
}

</style>
