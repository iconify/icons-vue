<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtevuubjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qtevuubjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:shopping-shipping-receipt-slip" /></template>
