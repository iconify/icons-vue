<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuzo8w5dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":360,"height":384};
const content = `<path class="wuzo8w5dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:paypal-alt" /></template>
