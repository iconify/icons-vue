<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_ewsowrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="z_ewsowrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-cart-subtract" /></template>
