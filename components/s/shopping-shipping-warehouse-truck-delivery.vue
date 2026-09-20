<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2firwxhd.css';
import '../../css/h/hla--sikh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m2firwxhd"/><path class="hla--sikh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:shopping-shipping-warehouse-truck-delivery" /></template>
