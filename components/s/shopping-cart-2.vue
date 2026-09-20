<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_hdugbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="e_hdugbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-cart-2" /></template>
