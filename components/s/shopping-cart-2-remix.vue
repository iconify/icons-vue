<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpabi1zht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qpabi1zht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:shopping-cart-2-remix" /></template>
