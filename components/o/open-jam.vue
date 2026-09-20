<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz4e6deay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:open-jam" /></template>
<style>
.xz4e6deay {
  fill: currentColor;
  d: path("M7 19.77v-1h5.5v-8.547l2.1 2.1l.708-.707L12 8.308l-3.308 3.308l.708.707l2.1-2.1V15H4.616q-.691 0-1.153-.462T3 13.385v-7.77q0-.69.463-1.152T4.615 4h14.77q.69 0 1.152.463T21 5.616v7.769q0 .69-.463 1.153T19.385 15H13.5v3.77H17v1z");
}

</style>
