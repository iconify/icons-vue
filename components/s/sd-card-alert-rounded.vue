<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukw9gybrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sd-card-alert-rounded" /></template>
<style>
.ukw9gybrq {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V9.095q0-.324.13-.629q.132-.304.349-.522L9.944 3.48q.217-.218.522-.348q.305-.131.628-.131h6.29q.691 0 1.154.463T19 4.615v14.77q0 .69-.462 1.152T17.384 21zM12 16.23q.31 0 .501-.21t.191-.481t-.191-.482t-.501-.21t-.501.21t-.191.482q0 .27.191.481q.192.21.501.21m.357-2.95q.143-.143.143-.357V9.269q0-.213-.143-.357T12 8.77t-.357.143t-.143.357v3.654q0 .214.143.357t.357.143t.357-.143");
}

</style>
