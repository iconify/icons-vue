<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytbgqzbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sms" /></template>
<style>
.ytbgqzbnb {
  fill: currentColor;
  d: path("M2 22V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18H6zm6.713-11.288Q9 10.425 9 10t-.288-.712T8 9t-.712.288T7 10t.288.713T8 11t.713-.288m4 0Q13 10.426 13 10t-.288-.712T12 9t-.712.288T11 10t.288.713T12 11t.713-.288m4 0Q17 10.426 17 10t-.288-.712T16 9t-.712.288T15 10t.288.713T16 11t.713-.288");
}

</style>
