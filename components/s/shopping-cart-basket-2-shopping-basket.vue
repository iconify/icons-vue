<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsai2gy0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zsai2gy0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-cart-basket-2-shopping-basket" /></template>
