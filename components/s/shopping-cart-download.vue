<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-w5j8bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-w5j8bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shopping-cart-download" /></template>
