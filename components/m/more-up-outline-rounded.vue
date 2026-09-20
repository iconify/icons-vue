<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocmmds8bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:more-up-outline-rounded" /></template>
<style>
.ocmmds8bc {
  fill: currentColor;
  d: path("M17 7H9q-.425 0-.712-.288T8 6t.288-.712T9 5h9q.425 0 .713.288T19 6v9q0 .425-.288.713T18 16t-.712-.288T17 15zm-5 5H4q-.425 0-.712-.288T3 11t.288-.712T4 10h9q.425 0 .713.288T14 11v9q0 .425-.288.713T13 21t-.712-.288T12 20z");
}

</style>
