<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1uqqybxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:toolbar-rounded" /></template>
<style>
.x1uqqybxv {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V9h16v9.385q0 .69-.462 1.153T18.384 20zM4 8V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616V8z");
}

</style>
