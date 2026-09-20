<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clk6xjb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clk6xjb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:t-shirt-linear" /></template>
