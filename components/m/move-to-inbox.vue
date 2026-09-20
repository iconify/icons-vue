<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6siaj2xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:move-to-inbox" /></template>
<style>
.e6siaj2xb {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm8.109-3.934q.775-.55 1.075-1.45H19v-9q0-.27-.173-.443T18.385 5H5.615q-.269 0-.442.173T5 5.616v9h4.2q.3.9 1.075 1.45t1.725.55t1.725-.55M12 13.308L8.692 10l.708-.72l2.1 2.1V6.693h1v4.689l2.1-2.1l.708.719z");
}

</style>
