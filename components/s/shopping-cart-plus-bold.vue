<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsclkac7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rsclkac7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:shopping-cart-plus-bold" /></template>
