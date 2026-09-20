<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3-7b0-ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stock-media" /></template>
<style>
.h3-7b0-ux {
  fill: currentColor;
  d: path("M4.616 14q-.691 0-1.153-.462T3 12.385v-7.77q0-.69.463-1.153T4.615 3h7.77q.69 0 1.152.463T14 4.615v7.77q0 .69-.462 1.152T12.385 14zM8 11.75L6.8 10.1L5.385 12h6.23L9.7 9.5zm6.73 8.52Q14 19.537 14 18.5t.73-1.77T16.5 16q.448 0 .82.146t.68.413V11h3v1h-2v6.5q0 1.039-.73 1.77T16.5 21t-1.77-.73");
}

</style>
