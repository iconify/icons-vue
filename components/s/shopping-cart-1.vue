<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0tbg8bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="x0tbg8bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-cart-1" /></template>
