<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xknvo9bkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pinboard-outline-sharp" /></template>
<style>
.xknvo9bkq {
  fill: currentColor;
  d: path("m6.808 21l-.5-.5v-4.27H3v-1l1.423-2.86V9.384H3v-1h7.616v1H9.192v2.984l1.424 2.862v1H7.308v4.27zm5.634-2v-1H20V6H3V5h18v14zm-8.296-3.77H9.47l-1.278-2.54V9.385H5.423v3.304zm2.662 0");
}

</style>
