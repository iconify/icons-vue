<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2psk7i5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-found-savings-rounded" /></template>
<style>
.o2psk7i5j {
  fill: currentColor;
  d: path("M9.423 19H5.615q-.69 0-1.153-.462T4 17.384V4.616q0-.691.463-1.153T5.616 3h12.769q.69 0 1.153.463T20 4.616v12.769q0 .69-.462 1.153T18.384 19h-3.807l-2.012 2.011q-.242.243-.565.243t-.566-.243zM12 15.5q1.939 0 3.22-1.356T16.5 11V7.308q0-.348-.23-.578t-.578-.23H12q-1.814 0-3.157 1.28T7.5 11q0 .673.241 1.367q.242.694.694 1.385l-.689.67q-.165.164-.165.353t.165.354t.351.153q.186-.013.357-.172l.682-.62q.62.483 1.38.747q.761.263 1.484.263m1.07-5.163q0 .201-.166.367l-2.663 2.663q-.166.166-.357.156q-.192-.01-.357-.156q-.16-.165-.17-.356q-.009-.192.15-.351l2.69-2.689q.165-.165.353-.165t.354.165t.165.367");
}

</style>
