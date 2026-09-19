<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5zcy4b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w5zcy4b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:shopping-cart-20-solid" /></template>
