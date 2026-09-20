<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1b8s-ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:surgical" /></template>
<style>
.g1b8s-ber {
  fill: currentColor;
  d: path("m11.65 14.58l-2.327-2.326l7.03-7.031q.243-.242.569-.242t.569.242l1.19 1.19q.242.243.242.569t-.242.568zm1.196 4.632l1-1h8.289v1zm-7.136.019q-.689 0-1.338-.2t-1.218-.596l5.106-5.1l1.888 1.888q.216.215.348.483q.133.267.133.575t-.123.587t-.339.495l-.475.495q-.665.684-1.554 1.028t-1.828.345z");
}

</style>
