<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffdhr2xjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sms-outline-sharp" /></template>
<style>
.ffdhr2xjq {
  fill: currentColor;
  d: path("M8.713 10.713Q9 10.425 9 10t-.288-.712T8 9t-.712.288T7 10t.288.713T8 11t.713-.288m4 0Q13 10.426 13 10t-.288-.712T12 9t-.712.288T11 10t.288.713T12 11t.713-.288m4 0Q17 10.426 17 10t-.288-.712T16 9t-.712.288T15 10t.288.713T16 11t.713-.288M2 22V2h20v16H6zm3.15-6H20V4H4v13.125zM4 16V4z");
}

</style>
