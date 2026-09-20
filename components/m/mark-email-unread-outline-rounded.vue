<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvg4bzs1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mark-email-unread-outline-rounded" /></template>
<style>
.fvg4bzs1r {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h9q.425 0 .713.288T14 5t-.288.713T13 6H4v12h16v-7q0-.425.288-.712T21 10t.713.288T22 11v7q0 .825-.587 1.413T20 20zM4 6v12zm8 5l3.225-2q.35-.225.663-.112t.487.387t.125.6t-.4.55l-3.575 2.25q-.25.15-.525.15t-.525-.15L4 8V6zm4.875-3.875Q16 6.25 16 5t.875-2.125T19 2t2.125.875T22 5t-.875 2.125T19 8t-2.125-.875");
}

</style>
