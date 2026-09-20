<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzh3u1kac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shuffle-sharp" /></template>
<style>
.uzh3u1kac {
  fill: currentColor;
  d: path("M14.23 19v-1h3.1l-3.52-3.521l.713-.713L18 17.242v-2.954h1V19zm-8.522 0L5 18.292L17.292 6h-3.061V5H19v4.712h-1V6.708zm3.678-8.925L5 5.689L5.689 5l4.386 4.387z");
}

</style>
