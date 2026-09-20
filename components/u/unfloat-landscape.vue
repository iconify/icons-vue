<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgub7db-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:unfloat-landscape" /></template>
<style>
.bgub7db-p {
  fill: currentColor;
  d: path("m11.075 14.5l1.425-1.425L9.4 10H12V8H6v6h2v-2.575l3.075 3.075ZM17 20v-7h5v7h-5ZM4 20q-.825 0-1.413-.588T2 18V6q0-.825.588-1.413T4 4h16q.825 0 1.413.588T22 6v5h-7v9H4Z");
}

</style>
