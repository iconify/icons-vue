<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz8vqobuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-week-outline-rounded" /></template>
<style>
.fz8vqobuf {
  fill: currentColor;
  d: path("M4.616 18h4.057V6H4.616q-.27 0-.443.173T4 6.616v10.769q0 .269.173.442t.443.173m5.057 0h4.654V6H9.673zm5.654 0h4.058q.269 0 .442-.173t.173-.443V6.616q0-.27-.173-.443T19.385 6h-4.058zM4.616 19q-.691 0-1.153-.463T3 17.385V6.615q0-.69.463-1.152T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19z");
}

</style>
