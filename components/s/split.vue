<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8to-gp5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:split" /></template>
<style>
.h8to-gp5m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3.25H6.875q-2.123 0-3.624 1.501T1.75 8.375v7.25q0 2.123 1.501 3.624t3.624 1.501h5.124q-.114 0-.223-.034q-.11-.035-.204-.1t-.164-.155q-.07-.091-.11-.198l-1.5-4q-.033-.088-.044-.182t.004-.187q.013-.094.049-.181t.093-.163L12.563 12L9.9 8.45q-.057-.076-.093-.163t-.049-.181t-.004-.187t.044-.182l1.5-4q.04-.108.11-.198t.165-.155t.203-.1T12 3.25m0 0q.136 0 .263.048q.14.052.249.154t.171.238t.067.285t-.048.288l-1.355 3.616L14.1 11.55q.036.048.064.102t.048.111t.028.117q.01.06.01.12t-.01.12t-.028.117q-.02.058-.048.111q-.028.054-.064.102l-2.753 3.671l1.355 3.616q.053.139.048.288q-.005.15-.067.285q-.062.136-.171.238t-.249.154q-.127.048-.262.048h5.124q2.123 0 3.624-1.501t1.501-3.624v-7.25q0-2.123-1.501-3.624T17.125 3.25z");
}

</style>
