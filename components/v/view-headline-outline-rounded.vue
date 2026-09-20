<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcfvscbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-headline-outline-rounded" /></template>
<style>
.dcfvscbex {
  fill: currentColor;
  d: path("M4.975 15q-.425 0-.7-.288T4 14t.288-.712T5 13h14.025q.425 0 .7.288T20 14t-.288.713T19 15zm0 4q-.425 0-.7-.288T4 18t.288-.712T5 17h14.025q.425 0 .7.288T20 18t-.288.713T19 19zm0-8q-.425 0-.7-.288T4 10t.288-.712T5 9h14.025q.425 0 .7.288T20 10t-.288.713T19 11zm0-4q-.425 0-.7-.288T4 6t.288-.712T5 5h14.025q.425 0 .7.288T20 6t-.288.713T19 7z");
}

</style>
