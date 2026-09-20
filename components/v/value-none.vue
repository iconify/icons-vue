<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6448q3ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x6448q3ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:value-none" /></template>
