<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axfin_bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:turn-left-outline-rounded" /></template>
<style>
.axfin_bxk {
  fill: currentColor;
  d: path("m6.8 11l.9.9q.275.275.275.7t-.275.7t-.7.275t-.7-.275l-2.6-2.6q-.3-.3-.3-.7t.3-.7l2.6-2.6q.275-.275.7-.275t.7.275t.275.7t-.275.7l-.9.9H15q.825 0 1.413.588T17 11v8q0 .425-.288.713T16 20t-.712-.288T15 19v-8z");
}

</style>
