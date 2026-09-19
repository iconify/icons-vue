<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skcmv7x3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-pin-invoke" /></template>
<style>
.skcmv7x3p {
  fill: currentColor;
  d: path("M22 12v6c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2h10v2H4v12h16v-6zm0-5c0-1.66-1.34-3-3-3s-3 1.34-3 3s1.34 3 3 3s3-1.34 3-3M9.34 12h2.24l-2.95 2.95l1.41 1.41L13 13.42v2.24h2V10H9.34z");
}

</style>
