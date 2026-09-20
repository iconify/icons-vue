<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxx_iibyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:work-update-outline" /></template>
<style>
.xxx_iibyg {
  fill: currentColor;
  d: path("M4 18.385V19V8zM4.615 20q-.69 0-1.153-.462T3 18.384V8.616q0-.691.463-1.153T4.615 7H9V5.615q0-.69.463-1.153T10.616 4h2.769q.69 0 1.153.462T15 5.615V7h4.385q.69 0 1.152.463T21 8.616v4.198q-.239-.152-.479-.265q-.24-.112-.521-.21V8.616q0-.27-.173-.443T19.385 8H4.615q-.269 0-.442.173T4 8.616v9.769q0 .269.173.442t.443.173h7.459q.056.275.12.516q.063.24.153.484zM10 7h4V5.615q0-.269-.173-.442T13.385 5h-2.77q-.269 0-.442.173T10 5.615zm5.165 13.836Q14 19.67 14 18t1.165-2.835T18 14t2.836 1.165T22 18t-1.164 2.836T18 22t-2.835-1.164m2.835-.24l2.539-2.538l-.547-.546l-1.608 1.607v-3.715h-.769v3.715l-1.607-1.607l-.547.546z");
}

</style>
