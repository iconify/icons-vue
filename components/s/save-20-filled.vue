<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f1-hazdqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:save-20-filled" /></template>
<style>
.f1-hazdqi {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2-2h1v3.5A1.5 1.5 0 0 0 7.5 8h4A1.5 1.5 0 0 0 13 6.5V3h.379a2 2 0 0 1 1.414.586l1.621 1.621A2 2 0 0 1 17 6.621V15a2 2 0 0 1-2 2v-5.5a1.5 1.5 0 0 0-1.5-1.5h-7A1.5 1.5 0 0 0 5 11.5V17a2 2 0 0 1-2-2zm9-2H7v3.5a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5zm2 8.5V17H6v-5.5a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 .5.5");
}

</style>
