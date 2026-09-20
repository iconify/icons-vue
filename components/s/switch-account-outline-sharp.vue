<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qna4_szai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:switch-account-outline-sharp" /></template>
<style>
.qna4_szai {
  fill: currentColor;
  d: path("M16.125 10.125Q17 9.25 17 8t-.875-2.125T14 5t-2.125.875T11 8t.875 2.125T14 11t2.125-.875M8 15.75q1.125-1.325 2.7-2.037T14 13t3.3.713T20 15.75V4H8zM6 18V2h16v16zm-4 4V6h2v14h14v2zM13.288 8.712Q13 8.425 13 8t.288-.712T14 7t.713.288T15 8t-.288.713T14 9t-.712-.288M10.7 16h6.6q-.725-.5-1.575-.75T14 15t-1.725.25T10.7 16M14 9.875");
}

</style>
