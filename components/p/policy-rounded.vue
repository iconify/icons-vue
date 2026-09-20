<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn-1p1btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:policy-rounded" /></template>
<style>
.gn-1p1btx {
  fill: currentColor;
  d: path("M11.694 20.817q-.15-.025-.28-.075q-2.952-1.125-4.683-3.816T5 11.1V6.817q0-.51.295-.923t.755-.6l5.385-2q.292-.106.565-.106t.566.106l5.384 2q.46.187.755.6t.295.923V11.1q0 1.498-.422 2.88t-1.14 2.674l-2.95-2.95q.237-.379.375-.814Q15 12.454 15 12q0-1.246-.877-2.123T12 9t-2.123.877T9 12t.877 2.123T12 15q.487 0 .941-.147q.455-.147.828-.441l3.071 3.065q-.911 1.067-1.933 1.903t-2.34 1.362q-.13.05-.27.075t-.297.025t-.306-.025m-1.107-7.404Q10 12.825 10 12t.588-1.412T12 10t1.413.588T14 12t-.587 1.413T12 14t-1.412-.587");
}

</style>
