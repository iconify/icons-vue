<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlc03bcgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nlc03bcgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:shopping-cart-fill-16" /></template>
