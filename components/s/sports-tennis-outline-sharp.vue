<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9j70wbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-tennis-outline-sharp" /></template>
<style>
.p9j70wbox {
  fill: currentColor;
  d: path("m3.56 19.308l-.714-.708l4.504-4.504q.737-.736.976-1.755t.24-3.11q0-1.335.592-2.62q.592-1.284 1.677-2.369q1.967-1.967 4.294-2.267t3.833 1.217q1.511 1.512 1.211 3.839t-2.261 4.288q-1.085 1.085-2.36 1.658t-2.629.573q-2.04 0-3.07.246q-1.028.246-1.79 1.008zm6.894-7.658q1.175 1.17 3.175.85t3.575-1.894q1.6-1.6 1.903-3.588t-.853-3.112q-1.181-1.162-3.128-.852t-3.572 1.89Q9.979 6.52 9.632 8.497q-.348 1.978.822 3.153m5.577 9.473q-.877-.877-.877-2.123t.877-2.123T18.154 16t2.123.877t.877 2.123t-.877 2.123t-2.123.877t-2.123-.877m3.535-.71q.588-.588.588-1.413t-.588-1.412T18.154 17t-1.413.588T16.154 19t.587 1.413t1.413.587t1.412-.587M18.154 19");
}

</style>
