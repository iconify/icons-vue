<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmmt3kb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sticker-add" /></template>
<style>
.zmmt3kb1q {
  fill: currentColor;
  d: path("M19 7V5h-2V4h2V2h1v2h2v1h-2v2zm-5.573 2.27l2.38-.674q.068-.565-.323-.985q-.392-.419-.984-.419q-.545 0-.926.382t-.382.926q0 .217.072.4q.07.183.163.37m-6 1.75l2.38-.674q.062-.565-.325-.985t-.991-.419q-.539 0-.919.382q-.38.381-.38.926q0 .217.072.4q.07.183.163.37m4.073 3.71q1.494 0 2.654-.922q1.16-.923 1.5-2.373L8.5 13.454q.592.627 1.367.952t1.633.325M15 19l4-4h-2q-.825 0-1.412.588T15 17zm.577 1H5.616q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h9.023q-.012.125-.018.244t-.005.256q0 2.027 1.428 3.456T19.5 9.385q.138 0 .256-.006T20 9.362v6.215z");
}

</style>
