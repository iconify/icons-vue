<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fievb2bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table-rows-outline-rounded" /></template>
<style>
.fievb2bmk {
  fill: currentColor;
  d: path("M19 18.385v-3.058H5v3.058q0 .269.173.442t.443.173h12.769q.269 0 .442-.173t.173-.442m0-4.058V9.673H5v4.654zm0-5.654V5.616q0-.27-.173-.443T18.384 5H5.616q-.27 0-.443.173T5 5.616v3.057zM5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
