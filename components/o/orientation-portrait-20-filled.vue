<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="durqzognv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:orientation-portrait-20-filled" /></template>
<style>
.durqzognv {
  fill: currentColor;
  d: path("M4.5 16a.5.5 0 0 1 .5.5v.25c0 .138.112.25.25.25h.25a.5.5 0 0 1 0 1h-.25C4.56 18 4 17.44 4 16.75v-.25a.5.5 0 0 1 .5-.5m4 1a.5.5 0 0 1 0 1h-1a.5.5 0 0 1 0-1zm6-10A1.5 1.5 0 0 1 16 8.5v8a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 9 16.5v-6a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1 0-1h1a.5.5 0 0 1 .5.5v-2A1.5 1.5 0 0 1 10.5 7zm-10 6a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-1 0v-1a.5.5 0 0 1 .5-.5m1-3a.5.5 0 0 1 0 1h-.25a.25.25 0 0 0-.25.25v.25a.5.5 0 0 1-1 0v-.25c0-.69.56-1.25 1.25-1.25zm4-8A3.5 3.5 0 0 1 13 5.5a.5.5 0 0 1-1 0a2.5 2.5 0 0 0-4.991-.217l.137-.137a.5.5 0 1 1 .708.708l-1 1a.5.5 0 0 1-.708 0l-1-1a.5.5 0 1 1 .708-.708l.152.153A3.5 3.5 0 0 1 9.5 2");
}

</style>
