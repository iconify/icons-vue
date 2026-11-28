<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xucjgnbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xucjgnbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:receipt-plus" /></template>
