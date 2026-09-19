<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwk08dzyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rwk08dzyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:shopping-cart-outlined" /></template>
