<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trh9iyblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trh9iyblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:paypal-fill" /></template>
