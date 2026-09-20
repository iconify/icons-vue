<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="godh3lben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-as-pdf-sharp" /></template>
<style>
.godh3lben {
  fill: currentColor;
  d: path("M9 12.5h1v-2h1.5l.5-.5V8l-.5-.5H9zm1-3v-1h1v1zm3 3h2.5l.5-.5V8l-.5-.5H13zm1-1v-3h1v3zm3 1h1v-2h1v-1h-1v-1h1v-1h-2zM6 18V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
