<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-8nfloan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-portrait-long-outline" /></template>
<style>
.o-8nfloan {
  fill: currentColor;
  d: path("M12.866 19v-1h3.5q.269 0 .451-.173q.183-.173.183-.442V5.615q0-.269-.173-.442T16.385 5H7.539V4h8.846q.67 0 1.143.472q.472.472.472 1.144v11.769q0 .67-.472 1.143q-.472.472-1.143.472zM5 9.77V7.845h.923v-2.23q0-.678.457-1.147T7.539 4q.167 0 .465.089q.298.088.652.23t.753.306q.399.166.787.325l1.007.441q.54.236 1.168.503q.454.218.724.612t.27.873v11.775q0 .856-.7 1.302t-1.46.1q-1.118-.458-2.251-.835t-1.858-.577q-.54-.13-.856-.584q-.317-.454-.317-1.02v-1.31H5v-1.922h.923V9.769zm7-2.897q-.927-.46-2.075-.972t-2.136-.863q-.327-.096-.597.106t-.269.529v11.886q0 .193.116.347q.115.154.307.192q1.021.275 2.153.71q1.132.436 2.059.827q.327.154.567-.01t.24-.49V7.469q0-.192-.105-.346q-.106-.154-.26-.25m-5.077-1.97V17.56zM17 5v13z");
}

</style>
