<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj_o9clok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-landscape-short-outline" /></template>
<style>
.wj_o9clok {
  fill: currentColor;
  d: path("M5 7.252v9.787zm10.192-2.45q0-.308-.25-.461q-.25-.155-.519-.058q-1.58.628-3.953 1.456T5.5 6.752q-.211.02-.356.154Q5 7.04 5 7.252v8.979q0 .346.26.567t.586.183q3.431-.487 5.72-1.497q2.29-1.009 3.222-1.509q.193-.096.298-.279q.106-.182.106-.394zm3.193 13.179H5.846v-1h12.539q.269 0 .442-.173t.173-.442V7.379q0-.27-.173-.442q-.173-.173-.442-.173h-2.693v-1h2.693q.69 0 1.153.462T20 7.379v8.987q0 .69-.462 1.152t-1.153.463m-12.539 0q-.805 0-1.326-.53T4 16.116H3v-1.693h1V9.321H3V7.63h1v-.383q0-.607.416-1.026q.415-.418 1.042-.474q2.5-.179 4.774-.973t3.882-1.442q.757-.315 1.418.169t.66 1.304v8.463q0 .518-.268.937t-.728.667q-.782.416-2.034.96t-2.602 1.02t-2.619.802t-2.095.328");
}

</style>
