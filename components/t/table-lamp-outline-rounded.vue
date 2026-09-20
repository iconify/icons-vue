<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8y9ze5rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-lamp-outline-rounded" /></template>
<style>
.f8y9ze5rp {
  fill: currentColor;
  d: path("M14 21q-.425 0-.712-.288T13 20t.288-.712T14 19h6q.425 0 .713.288T21 20t-.288.713T20 21zM5.525 9H9V5H7.275zm10.763 8.713Q16 17.425 16 17V8q0-.425-.288-.712T15 7h-4v3q0 .425-.288.713T10 11H4q-.55 0-.85-.45t-.075-.95L5.45 4.2q.25-.55.737-.875T7.275 3H9q.825 0 1.413.588T11 5h4q1.25 0 2.125.875T18 8v9q0 .425-.288.713T17 18t-.712-.288M5.525 9H9z");
}

</style>
