<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-mdt4b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="y-mdt4b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:shopping-cart-stroke-12" /></template>
