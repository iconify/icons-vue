<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic7zcbbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:summarize-outline" /></template>
<style>
.ic7zcbbwh {
  fill: currentColor;
  d: path("M8.568 8.568q.24-.24.24-.568t-.24-.568T8 7.192t-.568.24t-.24.568t.24.568t.568.24t.568-.24m0 4q.24-.24.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24t.568-.24m0 4q.24-.24.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24t.568-.24M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h9.961L20 8.423v9.962q0 .69-.462 1.153T18.384 20zm0-1h12.769q.269 0 .442-.173t.173-.442V9h-4V5H5.616q-.27 0-.443.173T5 5.616v12.769q0 .269.173.442t.443.173M5 5v4zv14z");
}

</style>
