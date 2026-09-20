<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y542u5i2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-as-pdf-outline-sharp" /></template>
<style>
.y542u5i2x {
  fill: currentColor;
  d: path("M9 12.5h1v-2h1.5l.5-.5V8l-.5-.5H9zm1-3v-1h1v1zm3 3h2.5l.5-.5V8l-.5-.5H13zm1-1v-3h1v3zm3 1h1v-2h1v-1h-1v-1h1v-1h-2zM6 18V2h16v16zm2-2h12V4H8zm-6 6V6h2v14h14v2zM8 4v12z");
}

</style>
