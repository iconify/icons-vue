<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5-fgacvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:policy" /></template>
<style>
.n5-fgacvv {
  fill: currentColor;
  d: path("M12 20.962q-3.014-.895-5.007-3.651T5 11.1V5.692l7-2.615l7 2.615V11.1q0 1.498-.422 2.88t-1.14 2.674l-2.95-2.95q.237-.379.375-.814Q15 12.454 15 12q0-1.246-.877-2.123T12 9t-2.123.877T9 12t.877 2.123T12 15q.487 0 .941-.147q.455-.147.828-.441l3.071 3.065q-1.011 1.167-2.18 2.11T12 20.962m-1.412-7.55Q10 12.826 10 12t.588-1.412T12 10t1.413.588T14 12t-.587 1.413T12 14t-1.412-.587");
}

</style>
