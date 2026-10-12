<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk1-9y_pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk1-9y_pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shopping-cart-filled" /></template>
