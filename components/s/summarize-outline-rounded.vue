<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl4sqllsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:summarize-outline-rounded" /></template>
<style>
.tl4sqllsy {
  fill: currentColor;
  d: path("M8.568 8.568q.24-.24.24-.568t-.24-.568T8 7.192t-.568.24t-.24.568t.24.568t.568.24t.568-.24m0 4q.24-.24.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24t.568-.24m0 4q.24-.24.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24t.568-.24M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h9.29q.323 0 .628.13q.305.132.522.349l3.465 3.465q.218.218.348.522q.131.305.131.628v9.29q0 .691-.462 1.154T18.384 20zm0-1h12.769q.269 0 .442-.173t.173-.442V9h-3.192q-.349 0-.578-.23T15 8.192V5H5.616q-.27 0-.443.173T5 5.616v12.769q0 .269.173.442t.443.173M5 5v4zv14z");
}

</style>
