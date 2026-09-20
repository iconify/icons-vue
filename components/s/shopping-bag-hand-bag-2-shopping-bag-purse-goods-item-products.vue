<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0rev_bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="i0rev_bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-bag-hand-bag-2-shopping-bag-purse-goods-item-products" /></template>
