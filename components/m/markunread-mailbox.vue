<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a01ijqyjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markunread-mailbox" /></template>
<style>
.a01ijqyjd {
  fill: currentColor;
  d: path("M4.616 21q-.691 0-1.153-.462T3 19.385v-8.77q0-.69.463-1.152T4.615 9h2V3h6.5v3.616h-5.5V14H10V9h9.385q.69 0 1.153.463T21 10.616v8.769q0 .69-.462 1.153T19.385 21z");
}

</style>
