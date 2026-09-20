<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfool6bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="bfool6bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-cart-basket-3-shopping-basket" /></template>
