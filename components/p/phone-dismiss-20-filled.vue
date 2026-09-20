<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="avqh4bckh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-dismiss-20-filled" /></template>
<style>
.avqh4bckh {
  fill: currentColor;
  d: path("M5.5 2A1.5 1.5 0 0 0 4 3.5v13A1.5 1.5 0 0 0 5.5 18h4.757a5.5 5.5 0 0 1-1.235-3H7.5a.5.5 0 0 1 0-1h1.522A5.5 5.5 0 0 1 14 9.022V3.5A1.5 1.5 0 0 0 12.5 2zm9 17a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m1.854-6.354a.5.5 0 0 1 0 .708L15.207 14.5l1.147 1.146a.5.5 0 0 1-.708.708L14.5 15.207l-1.146 1.147a.5.5 0 0 1-.708-.708l1.147-1.146l-1.147-1.146a.5.5 0 0 1 .708-.708l1.146 1.147l1.146-1.147a.5.5 0 0 1 .708 0");
}

</style>
