<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc5ah0biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-rows-rounded" /></template>
<style>
.oc5ah0biu {
  fill: currentColor;
  d: path("M4 21q-.425 0-.712-.288T3 20v-2.65q0-.425.288-.712T4 16.35h16q.425 0 .713.288t.287.712V20q0 .425-.288.713T20 21zm0-6.65q-.425 0-.712-.288T3 13.35v-2.725q0-.425.288-.712T4 9.625h16q.425 0 .713.288t.287.712v2.725q0 .425-.288.713T20 14.35zm0-6.725q-.425 0-.712-.288T3 6.626V4q0-.425.288-.712T4 3h16q.425 0 .713.288T21 4v2.625q0 .425-.288.713T20 7.625z");
}

</style>
