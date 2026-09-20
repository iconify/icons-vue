<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1-j1r2ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="u1-j1r2ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-store-1-store-shop-shops-stores" /></template>
