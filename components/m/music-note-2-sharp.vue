<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8hpstqvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:music-note-2-sharp" /></template>
<style>
.u8hpstqvv {
  fill: currentColor;
  d: path("M3.877 18.93Q3 18.055 3 16.809q0-1.247.877-2.124q.877-.876 2.123-.876q.575 0 1.091.204q.517.205.909.615V6.192l11.058-2v10.616q0 1.246-.877 2.123t-2.123.877t-2.124-.877q-.876-.877-.876-2.123t.876-2.123t2.124-.877q.575 0 1.091.205q.516.204.909.614V8.098L9 9.808v7q0 1.246-.877 2.123T6 19.808t-2.123-.877");
}

</style>
