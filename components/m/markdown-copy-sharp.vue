<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysi6g5pdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:markdown-copy-sharp" /></template>
<style>
.ysi6g5pdv {
  fill: currentColor;
  d: path("M7 18V2h13v16zm-4 4V6h2v14h11v2zm7.25-9h1.5V8.5h1v3h1.5v-3h1V13h1.5V7h-6.5z");
}

</style>
