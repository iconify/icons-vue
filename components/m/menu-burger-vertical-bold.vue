<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrepq8k1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrepq8k1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-burger-vertical-bold" /></template>
