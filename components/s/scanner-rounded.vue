<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlnkpjb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:scanner-rounded" /></template>
<style>
.zlnkpjb3q {
  fill: currentColor;
  d: path("M17.985 13L5.296 8.404q-.188-.073-.277-.246q-.088-.173-.015-.362q.073-.188.256-.287q.182-.098.37-.025L18.609 12.2q.73.277 1.061.854t.33 1.215v3.115q0 .691-.462 1.153T18.384 19H5.616q-.691 0-1.153-.462T4 17.384v-2.768q0-.691.463-1.153T5.616 13zm-7.331 3.5H17q.214 0 .357-.143T17.5 16t-.143-.357T17 15.5h-6.346q-.213 0-.357.143q-.143.143-.143.357t.143.357t.357.143m-3.105.049q.22-.22.22-.549t-.22-.549t-.549-.22t-.549.22t-.22.549t.22.549t.549.22t.549-.22");
}

</style>
