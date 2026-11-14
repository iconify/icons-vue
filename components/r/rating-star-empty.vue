<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1zu2jbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rating-star-empty" /></template>
<style>
.x1zu2jbbt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.114 5.594l.892 1.504q.413.696 1.202.873l1.706.384q1.365.308 1.798 1.639q.432 1.331-.492 2.383l-1.154 1.313q-.534.607-.459 1.413l.163 1.74q.13 1.395-1.003 2.218t-2.419.269l-1.606-.693q-.742-.32-1.484 0l-1.606.693q-1.286.554-2.419-.269T6.23 16.843l.163-1.741q.075-.805-.459-1.412L4.78 12.377q-.924-1.052-.492-2.383t1.798-1.639l1.706-.384q.789-.177 1.202-.873l.892-1.504Q10.601 4.391 12 4.391t2.114 1.203");
}

</style>
