<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0e90mbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0e90mbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shopping-cart-2-fill" /></template>
