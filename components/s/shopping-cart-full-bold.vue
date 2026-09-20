<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpm6mobiy.css';
import '../../css/c/cuklhhb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpm6mobiy"/><path class="cuklhhb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shopping-cart-full-bold" /></template>
