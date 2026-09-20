<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrcllybqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:safety-check-sharp" /></template>
<style>
.yrcllybqb {
  fill: currentColor;
  d: path("M12 20.962q-3.014-.895-5.007-3.651T5 11.1V5.692l7-2.615l7 2.615V11.1q0 3.454-1.993 6.21T12 20.963m2.836-6.107Q16 13.69 16 12.019t-1.164-2.835T12 8.019T9.165 9.184T8 12.019t1.165 2.836T12 16.019t2.836-1.164m-1.186-.64l-2.034-2.034V9.135h.769v2.723l1.811 1.811z");
}

</style>
