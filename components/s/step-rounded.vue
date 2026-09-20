<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r77020bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:step-rounded" /></template>
<style>
.r77020bir {
  fill: currentColor;
  d: path("M19 15q-1.275 0-2.137-.862T16 12t.863-2.137T19 9t2.138.863T22 12t-.862 2.138T19 15m-8.825-2H3q-.425 0-.712-.288T2 12t.288-.712T3 11h7.175L8.3 9.1q-.275-.275-.288-.687T8.3 7.7q.275-.275.7-.275t.7.275l3.6 3.6q.3.3.3.7t-.3.7l-3.6 3.6q-.3.3-.7.288t-.7-.313q-.275-.3-.288-.7t.288-.7z");
}

</style>
