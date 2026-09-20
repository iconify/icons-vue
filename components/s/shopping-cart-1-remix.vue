<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4yzf1vmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y4yzf1vmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-cart-1-remix" /></template>
