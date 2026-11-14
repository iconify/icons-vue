<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p7gc8-82c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:threat-actor-20-filled" /></template>
<style>
.p7gc8-82c {
  fill: currentColor;
  d: path("M18 13a4 4 0 0 1-4 4h-.094a4 4 0 0 1-2.828-1.172l-.724-.724a.5.5 0 0 0-.708 0l-.725.724A4 4 0 0 1 6.093 17H6a4 4 0 0 1-4-4v-2h16zM4.269 12a2 2 0 1 0 3.463 2zm7.999 1.999a2 2 0 0 0 3.463-2zM10 2a8 8 0 0 1 7.416 5H18a1 1 0 0 1 1 1v1a1 1 0 0 1-1 1H2a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h.584A8 8 0 0 1 10 2");
}

</style>
