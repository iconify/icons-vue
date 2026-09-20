<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o0__whzto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:wallet-20-filled" /></template>
<style>
.o0__whzto {
  fill: currentColor;
  d: path("M4.5 3A1.5 1.5 0 0 0 3 4.5v10A2.5 2.5 0 0 0 5.5 17H15a2 2 0 0 0 2-2V7a2 2 0 0 0-1-1.732V5a2 2 0 0 0-2-2zM15 5H4.5a.5.5 0 0 1 0-1H14a1 1 0 0 1 1 1m-1.5 6h1a.5.5 0 0 1 0 1h-1a.5.5 0 0 1 0-1");
}

</style>
