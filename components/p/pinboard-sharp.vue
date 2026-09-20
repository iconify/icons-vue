<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc0j02btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pinboard-sharp" /></template>
<style>
.qc0j02btc {
  fill: currentColor;
  d: path("m6.808 21l-.5-.5v-4.27H3v-1l1.423-2.86V9.384H3v-1h7.616v1H9.192v2.984l1.424 2.862v1H7.308v4.27zm5.634-2v-1H20V6H3V5h18v14z");
}

</style>
