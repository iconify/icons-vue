<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv1i2gnkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zv1i2gnkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:money-currency-euro-exchange-payment-euro-forex-finance-currency-money-foreign" /></template>
