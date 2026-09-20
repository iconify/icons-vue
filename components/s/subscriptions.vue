<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxj4hkczo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subscriptions" /></template>
<style>
.vxj4hkczo {
  fill: currentColor;
  d: path("M4.616 21q-.691 0-1.153-.462T3 19.385v-8.77q0-.69.463-1.152T4.615 9h14.77q.69 0 1.152.463T21 10.616v8.769q0 .69-.463 1.153T19.385 21zm5.884-2.923L15.116 15L10.5 11.923zm-6-10.846v-1h15v1zm3-2.77v-1h9v1z");
}

</style>
