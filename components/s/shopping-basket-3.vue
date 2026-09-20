<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxa1xlbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxa1xlbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:shopping-basket-3" /></template>
