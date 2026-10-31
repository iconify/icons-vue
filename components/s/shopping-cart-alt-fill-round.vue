<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy4cxcjtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy4cxcjtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-cart-alt-fill-round" /></template>
