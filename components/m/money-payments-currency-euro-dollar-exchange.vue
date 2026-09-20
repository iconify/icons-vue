<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6u9q2rkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u6u9q2rkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:money-payments-currency-euro-dollar-exchange" /></template>
