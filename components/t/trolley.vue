<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0cz2eb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trolley" /></template>
<style>
.n0cz2eb4p {
  fill: currentColor;
  d: path("M5 17V5H2.5V4H6v12h15v1zm1.442 3.885q-.613 0-1.037-.425t-.424-1.037t.424-1.037t1.037-.425t1.038.424t.424 1.038t-.424 1.038t-1.038.424M7.77 14.23V9.769h4.462v4.462zm7 0V9.769h4.462v4.462zm3.722 6.23q-.414-.424-.414-1.038t.414-1.037q.415-.425 1.026-.425q.612 0 1.048.424T21 19.423t-.435 1.038t-1.048.424t-1.026-.425");
}

</style>
