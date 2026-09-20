<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da79h8b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-ticket-sharp" /></template>
<style>
.da79h8b_e {
  fill: currentColor;
  d: path("M5 23V1h14v5.1h1v4.8h-1V23zm3-7h8v-3q-.425 0-.712-.288T15 12t.288-.712T16 11V8H8v3q.425 0 .713.288T9 12t-.288.713T8 13zm3.65-1.65q-.15-.15-.15-.35t.15-.35t.35-.15t.35.15t.15.35t-.15.35t-.35.15t-.35-.15m0-2q-.15-.15-.15-.35t.15-.35t.35-.15t.35.15t.15.35t-.15.35t-.35.15t-.35-.15m0-2q-.15-.15-.15-.35t.15-.35t.35-.15t.35.15t.15.35t-.15.35t-.35.15t-.35-.15");
}

</style>
