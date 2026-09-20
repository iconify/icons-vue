<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itinflbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="itinflbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:money-currency-bitcoin-crypto-circle-payment-blokchain-finance-bitcoin-currency-money" /></template>
