<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azafrgb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="azafrgb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:money-cashier-tag-codes-tags-tag-product-label" /></template>
