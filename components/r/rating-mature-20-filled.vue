<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ktiitdbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rating-mature-20-filled" /></template>
<style>
.ktiitdbfx {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm4.924 1.235A.5.5 0 0 0 7 7.5v5a.5.5 0 1 0 1 0V9.243l1.576 2.522a.5.5 0 0 0 .848 0L12 9.243V12.5a.5.5 0 1 0 1 0v-5a.5.5 0 0 0-.924-.265L10 10.557z");
}

</style>
