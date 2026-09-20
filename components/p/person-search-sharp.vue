<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9ipoeioj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-search-sharp" /></template>
<style>
.t9ipoeioj {
  fill: currentColor;
  d: path("M11 11.385q-1.246 0-2.123-.877T8 8.385t.877-2.123T11 5.385t2.123.877T14 8.385t-.877 2.123t-2.123.877m10.216 10.538l-2.662-2.661q-.487.338-1.01.5t-1.044.161q-1.433 0-2.428-.995t-.995-2.428t.995-2.428t2.428-.995t2.428.995t.995 2.428q0 .521-.161 1.044t-.5 1.01l2.661 2.662zm-2.989-3.696q.696-.696.696-1.727t-.696-1.727t-1.727-.696t-1.727.696t-.696 1.727t.696 1.727t1.727.696t1.727-.696m-6.356-4.573q-.646 1.185-.761 2.462q-.116 1.276.415 2.5H4v-1.641q0-.639.358-1.161t.973-.841q1.082-.534 2.808-1.004t3.732-.315");
}

</style>
