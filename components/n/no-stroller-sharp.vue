<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egzr655pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:no-stroller-sharp" /></template>
<style>
.egzr655pl {
  fill: currentColor;
  d: path("M5.953 19.932q-.414-.415-.414-1.009t.414-1.008q.414-.415 1.008-.415t1.01.415t.414 1.008t-.415 1.009t-1.009.414t-1.008-.414m9.74-7.065l-3.372-3.37l3.418-3.995q.378-.454.907-.728t1.139-.274q.88 0 1.48.6t.6 1.48V7h-1v-.42q0-.459-.31-.77q-.31-.31-.77-.31q-.366 0-.687.167q-.321.168-.573.445l-.833.97zm-1.212 1.614l2.013 2.019H6.352l4.023-4.71l-8.321-8.315l.708-.714l18.9 18.9l-.714.708l-7.888-7.888zm.25 5.865q-.594 0-1.009-.414q-.414-.415-.414-1.009t.414-1.008t1.009-.415t1.009.415t.414 1.008t-.415 1.009t-1.008.414M11.266 8.441L7.814 4.988q.652-.234 1.334-.361q.683-.127 1.39-.127q.895 0 1.77.179q.877.179 1.723.517z");
}

</style>
