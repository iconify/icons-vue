<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqqcsabyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqqcsabyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:mobile-shopping-cart-exchange-bold" /></template>
