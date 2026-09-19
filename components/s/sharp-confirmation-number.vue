<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpr_aihvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-confirmation-number" /></template>
<style>
.kpr_aihvp {
  fill: currentColor;
  d: path("M22 10V4H2.01v6c1.1 0 1.99.9 1.99 2s-.89 2-2 2v6h20v-6c-1.1 0-2-.9-2-2s.9-2 2-2m-9 7.5h-2v-2h2zm0-4.5h-2v-2h2zm0-4.5h-2v-2h2z");
}

</style>
