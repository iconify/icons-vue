<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxxx8-_sp.css';
import '../../css/h/hp5jyobim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fxxx8-_sp"/><path class="hp5jyobim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:money-payments-credit-card-visa" /></template>
