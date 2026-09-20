<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7s5u-sdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="u7s5u-sdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-cart-3" /></template>
