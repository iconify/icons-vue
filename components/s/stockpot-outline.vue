<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7ek31buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stockpot-outline" /></template>
<style>
.q7ek31buv {
  fill: currentColor;
  d: path("M3 8h18v9q0 1.25-.875 2.125T18 20H6q-1.25 0-2.125-.875T3 17zm2 2v7q0 .425.288.713T6 18h12q.425 0 .713-.288T19 17v-7zM3 7V5h6V4q0-.425.288-.712T10 3h4q.425 0 .713.288T15 4v1h6v2zm9 7");
}

</style>
