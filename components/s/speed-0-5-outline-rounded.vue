<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk6oh01ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-0-5-outline-rounded" /></template>
<style>
.hk6oh01ne {
  fill: currentColor;
  d: path("M11 17q-.425 0-.712-.288T10 16t.288-.712T11 15h3v-2h-3q-.425 0-.712-.288T10 12V8q0-.425.288-.712T11 7h4q.425 0 .713.288T16 8t-.288.713T15 9h-3v2h2q.825 0 1.413.588T16 13v2q0 .825-.587 1.413T14 17zm-3.713-.288Q7 16.426 7 16t.288-.712T8 15t.713.288T9 16t-.288.713T8 17t-.712-.288");
}

</style>
