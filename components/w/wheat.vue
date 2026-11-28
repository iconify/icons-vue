<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgv_cbb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgv_cbb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wheat" /></template>
