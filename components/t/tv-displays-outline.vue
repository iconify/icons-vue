<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6-x1rb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-displays-outline" /></template>
<style>
.y6-x1rb0k {
  fill: currentColor;
  d: path("M3 15.327V4.616q0-.672.472-1.144T4.616 3h12.653v1H4.616q-.27 0-.443.173T4 4.616v10.711zM11.52 21v-2H8.384q-.69 0-1.153-.462t-.463-1.153v-9q0-.69.463-1.153t1.153-.463h12.019q.69 0 1.153.463t.462 1.153v9q0 .69-.462 1.153T20.404 19H17.25v2zm-3.135-3h12.019q.269 0 .442-.173t.173-.442v-9q0-.27-.173-.443t-.442-.173H8.384q-.268 0-.442.173q-.173.173-.173.442v9q0 .27.173.443q.174.173.443.173m6.019-5.116");
}

</style>
