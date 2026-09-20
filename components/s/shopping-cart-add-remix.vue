<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpc9mhzvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fpc9mhzvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-cart-add-remix" /></template>
