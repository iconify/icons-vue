<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c682etbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:skillet-cooktop" /></template>
<style>
.c682etbfs {
  fill: currentColor;
  d: path("M6 14.346q-.846 0-1.423-.577T4 12.346V9h12.006q.028-.748.473-1.35t1.167-.838l4.202-1.416l.318.939l-4.203 1.415q-.434.139-.699.516q-.264.378-.264.838v3.242q0 .827-.577 1.413T15 14.346zM10 20v-2.27q0-.268-.173-.441q-.173-.174-.442-.174H3v-1h6.385q.67 0 1.143.473q.472.471.472 1.143V20zm3 0v-2.27q0-.67.472-1.142t1.144-.472H21v1h-6.384q-.27 0-.443.173q-.173.172-.173.442V20z");
}

</style>
