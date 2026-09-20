<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhx2emb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stay-primary-portrait-outline-sharp" /></template>
<style>
.vhx2emb3t {
  fill: currentColor;
  d: path("M12 17q-.425 0-.712-.288T11 16t.288-.712T12 15t.713.288T13 16t-.288.713T12 17m-1-4V7h2v6zM5 23V1h14v22zm2-3v1h10v-1zm0-2h10V6H7zM7 4h10V3H7zm0 0V3zm0 16v1z");
}

</style>
