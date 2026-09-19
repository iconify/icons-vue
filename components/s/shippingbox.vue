<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdz380bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zdz380bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:shippingbox" /></template>
