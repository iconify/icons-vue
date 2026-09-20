<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg51wqbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-outline" /></template>
<style>
.dg51wqbmy {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h10.788q.69 0 1.153.463t.462 1.153v14.769q0 .69-.462 1.153T17.404 21zm0-1h10.788q.269 0 .442-.173t.173-.442V4.615q0-.269-.173-.442T17.404 4H6.616q-.27 0-.443.173T6 4.616v14.769q0 .269.173.442t.443.173m2.096-3.712h6.577V7.731H8.71zm1-1v-4.672h4.577v4.673zM12 6.538q.287 0 .48-.193t.193-.48t-.193-.48t-.48-.193t-.48.194t-.193.48t.193.48t.48.193m0 12.288q.287 0 .48-.193t.193-.48t-.193-.49t-.48-.202t-.48.203t-.193.489t.193.48t.48.193M12 12");
}

</style>
