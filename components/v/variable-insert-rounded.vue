<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6vi4nngg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:variable-insert-rounded" /></template>
<style>
.f6vi4nngg {
  fill: currentColor;
  d: path("M4 17q-.425 0-.712-.288T3 16V8q0-.425.288-.712T4 7h16q.425 0 .713.288T21 8v2q0 .425-.288.713T20 11h-4q-.825 0-1.412.588T14 13v3q0 .425-.288.713T13 17zm14-.575V18.5q0 .425-.288.713T17 19.5t-.712-.288T16 18.5V14q0-.425.288-.712T17 13h4.5q.425 0 .713.288T22.5 14t-.288.713T21.5 15h-2.1l2.9 2.875q.3.3.3.713t-.3.712t-.712.3t-.713-.3z");
}

</style>
