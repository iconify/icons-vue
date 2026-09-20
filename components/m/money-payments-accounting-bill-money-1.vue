<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1538reyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f1538reyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:money-payments-accounting-bill-money-1" /></template>
