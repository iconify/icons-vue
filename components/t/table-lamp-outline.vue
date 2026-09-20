<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz7mk7rht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-lamp-outline" /></template>
<style>
.gz7mk7rht {
  fill: currentColor;
  d: path("M13 21v-2h8v2zM5.525 9H9V5H7.275zM16 18V8q0-.425-.288-.712T15 7h-4v3q0 .425-.288.713T10 11H4q-.55 0-.85-.45t-.075-.95L5.45 4.2q.25-.55.737-.875T7.275 3H9q.825 0 1.413.588T11 5h4q1.25 0 2.125.875T18 8v10zM5.525 9H9z");
}

</style>
