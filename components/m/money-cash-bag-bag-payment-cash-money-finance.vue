<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orng1hbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="orng1hbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:money-cash-bag-bag-payment-cash-money-finance" /></template>
