<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klugf78fa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klugf78fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paint-bucket-fill-round" /></template>
