<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl-11ac0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-landscape-short" /></template>
<style>
.gl-11ac0e {
  fill: currentColor;
  d: path("M5.846 17.98q-.805 0-1.326-.529T4 16.116H3v-1.693h1V9.321H3V7.63h1v-.383q0-.607.416-1.026q.415-.418 1.042-.474q2.5-.179 4.774-.973t3.882-1.442q.757-.315 1.418.169t.66 1.304v8.463q0 .518-.268.937t-.728.667q-.782.416-2.034.96t-2.602 1.02t-2.619.802t-2.095.328m4.452 0q1.456-.472 2.801-1.056t2.566-1.202q.696-.367 1.093-1.02q.396-.653.396-1.436V5.764h1.23q.691 0 1.153.462T20 7.379v8.987q0 .69-.463 1.152t-1.153.463z");
}

</style>
