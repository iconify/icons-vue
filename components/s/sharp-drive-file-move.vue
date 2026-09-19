<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-fht_o0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-drive-file-move" /></template>
<style>
.s-fht_o0j {
  fill: currentColor;
  d: path("M22 6H12l-2-2H2v16h20zM12 17v-3H8v-2h4V9l4 4z");
}

</style>
