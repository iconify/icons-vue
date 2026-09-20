<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8y6kbcde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rectangle-add-rounded" /></template>
<style>
.h8y6kbcde {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm6.884-6.5V15q0 .213.144.356t.357.144t.356-.144T12.5 15v-2.5H15q.213 0 .356-.144t.144-.357t-.144-.356T15 11.5h-2.5V9q0-.213-.144-.356t-.357-.144t-.356.144T11.5 9v2.5H9q-.213 0-.356.144t-.144.357t.144.356T9 12.5z");
}

</style>
