<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntt3ssblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-scanner" /></template>
<style>
.ntt3ssblb {
  fill: currentColor;
  d: path("m4.2 5l-.7 1.9L17.6 12H3v8h18v-8.86zM7 17H5v-2h2zm12 0H9v-2h10z");
}

</style>
