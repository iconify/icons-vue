<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbupr_bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kbupr_bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-cart-add" /></template>
