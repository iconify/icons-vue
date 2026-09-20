<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_ytsz3hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:work-history" /></template>
<style>
.y_ytsz3hb {
  fill: currentColor;
  d: path("m19.65 20.196l.546-.546l-1.811-1.811v-2.723h-.77v3.046zM10 7h4V5.615q0-.269-.173-.442T13.385 5h-2.77q-.269 0-.442.173T10 5.615zm5.165 13.836Q14 19.67 14 18t1.165-2.835T18 14t2.836 1.165T22 18t-1.164 2.836T18 22t-2.835-1.164M4.615 20q-.69 0-1.152-.462T3 18.384V8.616q0-.691.463-1.153T4.615 7H9V5.615q0-.69.463-1.153T10.616 4h2.769q.69 0 1.153.462T15 5.615V7h4.385q.69 0 1.152.463T21 8.616v4.198q-.683-.414-1.448-.614T18 12q-2.496 0-4.248 1.752T12 18q0 .506.086 1.009t.262.991z");
}

</style>
