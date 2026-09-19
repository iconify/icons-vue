<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-r383bvg"/><path class="cooa6dyoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-logout" /></template>
<style>
.cooa6dyoq {
  fill: currentColor;
  d: path("m21 12l-4-4v3H9v2h8v3z");
}

.f-r383bvg {
  fill: currentColor;
  d: path("M5 5h7V3H3v18h9v-2H5z");
}

</style>
