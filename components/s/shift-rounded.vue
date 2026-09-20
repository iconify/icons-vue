<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqdxtjftk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shift-rounded" /></template>
<style>
.gqdxtjftk {
  fill: currentColor;
  d: path("M9 19.192V12.77H6.744q-.505 0-.74-.447q-.233-.447.071-.85l5.284-7.041q.25-.337.645-.337q.394 0 .637.337l5.284 7.04q.304.404.07.851t-.739.447H15v6.423q0 .344-.232.576t-.576.232H9.808q-.343 0-.576-.232T9 19.192");
}

</style>
