<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjb570f_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjb570f_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shopping-cart-add-01" /></template>
