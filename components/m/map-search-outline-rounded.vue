<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbr4jtbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:map-search-outline-rounded" /></template>
<style>
.cbr4jtbst {
  fill: currentColor;
  d: path("M15.5 10.23v-.038zV7.005zM5.042 19.355q-.384.142-.713-.084T4 18.634V6.404q0-.268.13-.489t.378-.307l3.958-1.345q.267-.086.534-.086t.535.086L15 6.177l3.958-1.53q.384-.143.713.054t.329.588v6.213q0 .214-.143.357t-.357.143t-.357-.143t-.143-.357V5.7l-3.5 1.304v2.885q0 .213-.143.356T15 10.39t-.357-.144t-.143-.356V7.004l-5-1.746v11.544q0 .379-.215.687q-.214.307-.562.444zM5 18.3l3.5-1.342v-11.7L5 6.45zm12.528-.733q.659-.644.664-1.663q.006-.985-.658-1.646q-.665-.662-1.65-.662t-1.646.662t-.661 1.646t.661 1.646t1.646.662t1.644-.645m-1.643 1.645q-1.362 0-2.335-.973t-.973-2.335t.973-2.335t2.334-.973t2.335.973t.973 2.335q0 .556-.166 1.049q-.167.493-.48.905l2.1 2.1q.14.14.15.344t-.13.344q-.141.16-.355.15q-.213-.01-.353-.15l-2.1-2.1q-.412.333-.905.5q-.494.165-1.069.165M8.5 5.259v11.7z");
}

</style>
