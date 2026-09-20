<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0dsanjek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="g0dsanjek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:money-currency-dollar-dollar-exchange-payment-forex-finance-currency-money-foreign" /></template>
