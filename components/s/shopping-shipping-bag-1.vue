<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdcu93bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zdcu93bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:shopping-shipping-bag-1" /></template>
