<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in_8m6pkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="in_8m6pkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:shopping-shipping-barcode" /></template>
