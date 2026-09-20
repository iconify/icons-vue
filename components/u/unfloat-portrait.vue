<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp3z59ejt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:unfloat-portrait" /></template>
<style>
.jp3z59ejt {
  fill: currentColor;
  d: path("m13.075 12.5l1.425-1.425L11.425 8H14V6H8v6h2V9.4l3.075 3.1ZM15 22v-7h5v7h-5Zm-9 0q-.825 0-1.412-.588T4 20V4q0-.825.588-1.413T6 2h12q.825 0 1.413.588T20 4v9h-7v9H6Z");
}

</style>
