<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1hy70kip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:new-label-outline" /></template>
<style>
.l1hy70kip {
  fill: currentColor;
  d: path("M12 20v-2h3l4.5-6L15 6H4v5H2V6q0-.825.588-1.412T4 4h11q.475 0 .9.213t.7.587L22 12l-5.4 7.2q-.275.375-.7.588T15 20zm-7 1v-3H2v-2h3v-3h2v3h3v2H7v3z");
}

</style>
