<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5e5623cj.css';
import '../../css/f/fjjuhwb3o.css';
import '../../css/k/k17j4pb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b5e5623cj"/><path class="fjjuhwb3o"/><path class="k17j4pb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:money-payments-cash-payment-coin" /></template>
