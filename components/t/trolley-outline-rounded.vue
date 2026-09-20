<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkoe6cc7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trolley-outline-rounded" /></template>
<style>
.qkoe6cc7g {
  fill: currentColor;
  d: path("M20.5 17H6.616q-.667 0-1.141-.475T5 15.386v-9.77q0-.269-.173-.442T4.385 5H3q-.213 0-.356-.144T2.5 4.499t.144-.356T3 4h1.385q.666 0 1.14.475T6 5.615v9.77q0 .269.173.442t.443.173H20.5q.213 0 .356.144t.144.357t-.144.356T20.5 17M6.442 20.885q-.613 0-1.037-.424t-.424-1.038t.424-1.037t1.037-.424t1.038.424t.424 1.037t-.424 1.038t-1.038.424m2.135-6.654q-.343 0-.575-.232t-.233-.576v-2.846q0-.343.232-.575t.576-.233h2.846q.343 0 .576.232t.232.576v2.846q0 .343-.232.576t-.576.232zm.192-1h2.462v-2.462H8.769zm6.808 1q-.343 0-.575-.232t-.233-.576v-2.846q0-.343.232-.575t.576-.233h2.846q.343 0 .576.232t.232.576v2.846q0 .343-.232.576t-.576.232zm.192-1h2.462v-2.462h-2.462zm2.722 7.23q-.414-.424-.414-1.038t.414-1.037t1.026-.424t1.048.424t.435 1.037t-.435 1.038t-1.048.424t-1.026-.424M8.77 13.23h2.462zm7 0h2.462z");
}

</style>
