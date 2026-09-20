<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-z63n3wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:settings-cell-outline-sharp" /></template>
<style>
.n-z63n3wv {
  fill: currentColor;
  d: path("M8 24q-.425 0-.712-.288T7 23t.288-.712T8 22t.713.288T9 23t-.288.713T8 24m4 0q-.425 0-.712-.288T11 23t.288-.712T12 22t.713.288T13 23t-.288.713T12 24m4 0q-.425 0-.712-.288T15 23t.288-.712T16 22t.713.288T17 23t-.288.713T16 24M6 20V0h12v20zm2-2h8v-1H8zm0-3h8V5H8zM8 3h8V2H8zm0 0V2zm0 15v-1z");
}

</style>
