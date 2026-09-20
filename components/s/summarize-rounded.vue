<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm917orri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:summarize-rounded" /></template>
<style>
.fm917orri {
  fill: currentColor;
  d: path("M8.568 8.568q.24-.24.24-.568t-.24-.568T8 7.192t-.568.24t-.24.568t.24.568t.568.24t.568-.24m0 4q.24-.24.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24t.568-.24m0 4q.24-.24.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24t.568-.24M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h9.29q.323 0 .628.13q.305.132.522.349l3.465 3.465q.218.218.348.522q.131.305.131.628v9.29q0 .691-.462 1.154T18.384 20zM15 5v3.192q0 .348.23.578t.578.23H19z");
}

</style>
