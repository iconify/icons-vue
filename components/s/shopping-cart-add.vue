<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0y8ghj5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0y8ghj5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shopping-cart-add" /></template>
