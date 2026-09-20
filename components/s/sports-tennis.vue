<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxta89bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-tennis" /></template>
<style>
.rxta89bqd {
  fill: currentColor;
  d: path("m3.56 19.308l-.714-.708l4.504-4.504q.737-.736.976-1.755t.24-3.11q0-1.335.592-2.62q.592-1.284 1.677-2.369q1.967-1.967 4.294-2.267t3.833 1.217q1.511 1.512 1.211 3.839t-2.261 4.288q-1.085 1.085-2.36 1.658t-2.629.573q-2.04 0-3.07.246q-1.028.246-1.79 1.008zm6.894-7.658q1.175 1.15 3.175.84t3.575-1.884q1.6-1.6 1.912-3.588t-.862-3.112q-1.162-1.181-3.128-.872t-3.572 1.91Q9.979 6.5 9.64 8.488t.813 3.162m5.577 9.473q-.877-.877-.877-2.123t.877-2.123T18.154 16t2.123.877t.877 2.123t-.877 2.123t-2.123.877t-2.123-.877");
}

</style>
