<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sydox8bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:more-outline-rounded" /></template>
<style>
.sydox8bgs {
  fill: currentColor;
  d: path("M9 20q-.475 0-.9-.213t-.7-.587l-4.5-6q-.4-.525-.4-1.2t.4-1.2l4.5-6q.275-.375.7-.587T9 4h11q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm0-2h11V6H9l-4.5 6zm1.713-5.288Q11 12.425 11 12t-.288-.712T10 11t-.712.288T9 12t.288.713T10 13t.713-.288m3.5 0q.287-.287.287-.712t-.288-.712T13.5 11t-.712.288T12.5 12t.288.713t.712.287t.713-.288m3.5 0Q18 12.426 18 12t-.288-.712T17 11t-.712.288T16 12t.288.713T17 13t.713-.288M12.25 12");
}

</style>
