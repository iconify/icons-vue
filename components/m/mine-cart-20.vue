<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz5nhebgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zz5nhebgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mine-cart-20" /></template>
