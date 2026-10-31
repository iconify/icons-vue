<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i536a978p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i536a978p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-cart-alt-round" /></template>
