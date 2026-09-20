<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvsu4fbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-kanban-outline-rounded" /></template>
<style>
.zvsu4fbgy {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm0-1h12.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192M5 5v14zm2.643 2.643Q7.5 7.787 7.5 8v8q0 .214.143.357T8 16.5t.357-.143T8.5 16V8q0-.213-.143-.357T8 7.5t-.357.143m8 0Q15.5 7.787 15.5 8v6q0 .214.143.357T16 14.5t.357-.143T16.5 14V8q0-.213-.143-.357T16 7.5t-.357.143m-4 0Q11.5 7.787 11.5 8v3q0 .214.143.357T12 11.5t.357-.143T12.5 11V8q0-.213-.143-.357T12 7.5t-.357.143");
}

</style>
